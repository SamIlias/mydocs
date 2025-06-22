# Neovim Cheatsheet

---

## File Navigation

- `:e filename` — open file
- `:Ex` — open file explorer
- `:w` — save
- `:q` — quit

---

## Scrolling

- `zz` — scroll so current line is **centered**
- `zb` — scroll so current line is **at bottom**
- `zt` — scroll so current line is **at top**

---

## Navigation

- `fx` / `Fx` — move **to** next/previous occurrence of `x`
- `tx` / `Tx` — move **right before** next/previous occurrence of `x`
- `;` / `,` — repeat/unrepeat last `f`, `F`, `t`, or `T` motion

---

## Mode Switching

- `<C-o>` — switch to **command mode** temporarily for one command

---

## Text Casing

- `~` — invert case of the character under the cursor
- `g~` + range (e.g. `g~e`, `g~$`, `g~iw`, `g~0`) — invert case over a range
- `gu` + range — lowercase over a range
- `gU` + range — UPPERCASE over a range

---

## Folding

- `zM` — close all folds
- `zm` — fold more (increase folding level)
- `zR` — open all folds
- `zr` — unfold one level
- `zO` — open **fold recursively** under cursor
- `zo` — open current fold

---

## Multicursor Editing (Visual Block)

1. `<C-v>` — enter **Visual Block** mode
2. Use `j` / `k` to select multiple lines
3. `$` — move to end of each line
4. `A` — append text at the end
5. Type your text
6. `<Esc>` — finish block insert

---

## Replacing

1. `: %s/old_text/new_text/g` Replace all occurrences in the current file

---

## Surround (via [nvim-surround](https://github.com/kylechui/nvim-surround))

- `ys{motion}{char}` — **add** surrounding
- `ds{char}` — **delete** surrounding
- `cs{target}{replacement}` — **change** surrounding

### Examples

| Old Text                   | Command     | New Text                |
| -------------------------- | ----------- | ----------------------- |
| `surr*ound_words`          | `ysiw)`     | `(surround_words)`      |
| `*make strings`            | `ys$"`      | `"make strings"`        |
| `[delete ar*ound me!]`     | `ds]`       | `delete around me!`     |
| `remove <b>HTML t*ags</b>` | `dst`       | `remove HTML tags`      |
| `'change quot*es'`         | `cs'"`      | `"change quotes"`       |
| `<b>or tag* types</b>`     | `csth1<CR>` | `<h1>or tag types</h1>` |
| `delete(functi*on calls)`  | `dsf`       | `function calls`        |

---

> ✅ Tip: Install `nvim-surround` with a plugin manager like `lazy.nvim`, `packer.nvim`, or `vim-plug` to use the surround shortcuts.
