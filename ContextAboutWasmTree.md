My repository https://github.com/BruJu/Portable-Reasoning-in-Web-Assembly tries
to exports Sophia Dataset : it is slow.

One of the suspect were the strings so my advisor told me "what if you only
export your tree structure from wasm, and do the string - index corresponding
in Javascript ?" (+ There are other reason like exporting everything causes
major memory leaks because Javascript does not have destructor)
