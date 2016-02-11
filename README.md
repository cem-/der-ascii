# DER ASCII

DER ASCII is a small human-editable language to emit DER-like output. Its goal
is to help create test inputs by taking an existing DER or BER structure,
disassembling it into DER ASCII, making adjustments, and assembling back into
DER. This avoids having to manually fix up all the length prefixes. As a bonus,
it acts as a human-readable view for DER structures.

For the language specification and basic examples, see
[language.txt](/language.txt). The [samples](/samples) directory includes
more complex examples from real inputs.

This project provides two tools, `ascii2der` and `der2ascii`, to convert DER
ASCII to a byte string and vice versa. To install them, run:

    go get github.com/google/der-ascii/cmd/...

This is not an official Google project.
