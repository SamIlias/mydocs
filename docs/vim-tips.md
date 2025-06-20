### FileNavigator

### Scrolling

z+z/z+b/z+t :: current line on center/bottom/top

### Navigation

fx (Fx) :: Navigation before the next(previous) occurrence of x character
tx (Tx) :: Navigation after the next(previous) occurrence of x character
; (,) :: repeat(unrepeat) f/F/t/T command

### Mode switching

ctrl+o: command mode only for one command

### Text casing

~ :: invert the case of the character under the cursor
g~(e/$/iw/0) :: followed by range inverts symbols
gu(e/$/iw/0) :: followed by range lowercases symbols
gU(e/$/iw/0) :: followed by range UPPERCASES symbols

### Folding

- zM :: closes all folds
- zm :: folds nested level by level
- zR :: open all folds
- zr :: open level by level
- zO ::
- zo ::

### Multicursor

- `<c-V>` - Enter Visual Block mode.
- Use `j`/`k` to select the lines.
- `$` - Move cursor to last character.
- `A` - Enter insert mode after last character.
- Insert desired text.
- `<Esc>` - Exit insert mode and finish block append.

### nvim surround (external tool)

The three "core" operations of `add`/`delete`/`change` can be done with the
keymaps `ys{motion}{char}`, `ds{char}`, and `cs{target}{replacement}`,
respectively. For the following examples, `*` will denote the cursor position:

```help
    Old text                    Command         New text
--------------------------------------------------------------------------------
    surr*ound_words             ysiw)           (surround_words)
    *make strings               ys$"            "make strings"
    [delete ar*ound me!]        ds]             delete around me!
    remove <b>HTML t*ags</b>    dst             remove HTML tags
    'change quot*es'            cs'"            "change quotes"
    <b>or tag* types</b>        csth1<CR>       <h1>or tag types</h1>
    delete(functi*on calls)     dsf             function calls
```
