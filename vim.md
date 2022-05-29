- move: hjkl
- insert: i a
- insert below: o
- insert above: O
- delete than insert: c
- delete after curser, than insert: C
- cut line than insert: S
- cut curser letter than insert: s
- yank (copy): y
- paste: p
- cut: d
- cut everything after curser: D

- forward: w
- beginning of content: _
- beginning of line: 0
- backward: b
- end of line: $
- line up: C-p
- line down: C-n
- top of file: gg
- end of file: G
- switch between 2 files: C-6
- back 1 file: C-o
- for 1 file: C-i
- half page down: C-d
- half page up: C-u
- next {: [m
- prev {: ]m
- jump between {}()[]: %
- jump between start and end of visual line: o

- delete all in {}: di{
	d = delete
	i = inside
	{ = in {}
	1st:
	v = visial mode
	V = visial line mode
	y = yank

	2nd:
	i = inside + {}

	2rd:
	- w = word until breaker (: { } ;)
	- W = word until space
- copy all in {}: yi{
	yank in {}

- move paragragh up: {
- move paragraph down: }

- in V
	Move selected up: K
	Move selected down: J	

FIND:
- find letter: f{letter}
- find next letter: ;
- find prev letter: ,
- find letter before better: t{letter}
- capital FT turns around

- visual mode (select) v

- delete 6 lines down: d6j
- jump 6 lines line down: 6j 

search/replace:
- search: /{string}
- replace: :[% = full]s/{search}/replace[g = all(selected)][c = y/c]


commands:
- :q - quit
- :PlugInstall - install plugins

filetree:
- :Ex - go back

add commands to config:
- :so % = save


macro: 
- start: q{letter}
- stop: q
- run: @{letter}
macro letter is in :reg


