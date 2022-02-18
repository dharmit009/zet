# VIM CTERM COLORS ... 

The vim **cterms** colors are used to make color schemes portable across
devices. Each number represents a color in the terminal. The **NR-16**
and **NR-8** colors are used for **16-bit** and **8-bit** terminal
colors. 

**CTERM COLORS**
--------------------
| NR-16 | NR-8  | COLOR NAME ~ |
|    0	|    0	|    Black |
|    1	|    4	|    DarkBlue|
|    2	|    2	|    DarkGreen|
|    3	|    6	|    DarkCyan|
|    4	|    1	|    DarkRed|
|    5	|    5	|    DarkMagenta|
|    6	|    3	|    Brown, DarkYellow|
|    7	|    7	|    LightGray, LightGrey, Gray, Grey|
|    8	|    0*	|    DarkGray, DarkGrey|
|    9	|    4*	|    Blue, LightBlue|
|    10	|    2*	|    Green, LightGreen|
|    11	|    6*	|    Cyan, LightCyan|
|    12	|    1*	|    Red, LightRed|
|    13	|    5*	|    Magenta, LightMagenta|
|    14	|    3*	|    Yellow, LightYellow|
|    15	|    7*	|    White|

  The '\*' indicates that the	bold attribute is set for ctermfg.  In many 8-color terminals (e.g., "linux"), this causes the bright colors to appear.  This doesn't work	for background colors!	Without the '*' the bold attribute is removed.
  
	If you want to set the bold attribute in a different way, put a
	"cterm=" argument AFTER the "ctermfg=" or "ctermbg=" argument.	Or use
	a number instead of a color name.


