# Wordlists
This is a collection of wordlists pulled from commonly used tools for discovery, enumeration, fuzzing, and exploitation.

## Full (Deep) Clone
```bash
git clone -j`nproc` --recursive https://github.com/drtychai/wordlists 
```

## Partial (Shallow) Clone

Skips: [big-list-of-naughty-strings][blns], [SecLists][seclst], [fuzzDB][fzzdb]
```bash
git clone -j`nproc` https://github.com/drtychai/wordlists 
```

[blns]: https://github.com/minimaxir/big-list-of-naughty-strings
[seclst]: https://github.com/danielmiessler/SecLists
[fzzdb]: https://github.com/fuzzdb-project/fuzzdb
