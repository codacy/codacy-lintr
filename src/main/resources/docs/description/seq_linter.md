Check for `1:length(...)`, `1:nrow(...)`, `1:ncol(...)`, `1:NROW(...)` and `1:NCOL(...)` expressions. These often cause bugs when the right hand side is zero. It is safer to use `seq_len` or `seq_along` instead.

[SOURCE](https://github.com/jimhester/lintr/blob/master/R/seq_linter.R)
