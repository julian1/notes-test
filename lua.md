

https://spin.atomicobject.com/2013/07/01/lua-coroutines/

#### Issues

how to do communication between coroutines?

  - shared state, with flags
  - messages on a stack, that the coroutines can test and consume?


#### refs

lua in 15 minutes intro http://tylerneylon.com/a/learn-lua/

lua underscore - map,filter,fold etc for lua https://mirven.github.io/underscore.lua/

function programming in lua examples https://en.wikibooks.org/wiki/Lua_Functional_Programming/Functions

more functional http://lua-users.org/wiki/FunctionalLibrary

wikipedia lua https://en.wikipedia.org/wiki/Lua_%28programming_language%29

#### advantages
  - coroutines
  - easy integration with c
  - first- class functions
  - fast
  - designed for embedded - small code and mem footprint
  - low dependencies

#### but
  - no standard library
  - off-by-one indexing
  - no debugger
  - limited unicode support  http://stackoverflow.com/questions/2497800/does-lua-support-unicode

used
  openwrt?

