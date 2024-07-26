UTF-8 is a variable-length character encoding standard used for electronic communication.
Defined by the Unicode Standard,
the name is derived from Unicode Transformation Format – 8-bit.[1]

UTF-8 is capable of encoding all 1,112,064 valid Unicode code points using one to four one-byte (8-bit) code units.
Code points with lower numerical values, which tend to occur more frequently, are encoded using fewer bytes.
It was designed for backward compatibility with ASCII: the first 128 characters of Unicode,
which correspond one-to-one with ASCII, are encoded using a single byte with the same binary value as ASCII,
so that valid ASCII text is valid UTF-8-encoded Unicode as well.

UTF-8 was designed as a superior alternative to UTF-1,
a proposed variable-length encoding with partial ASCII compatibility
which lacked some features including self-synchronization and fully ASCII-compatible handling of characters such as slashes.

UTF-8 results in fewer internationalization issues than any alternative text encoding,
and it has been implemented in all modern operating systems, including Microsoft Windows,
and standards such as JSON, where, as is increasingly the case, it is the only allowed form of Unicode.

UTF-8 is the dominant encoding for the World Wide Web (and internet technologies),
accounting for 98.2% of all web pages, 99.1% of the top 100,000 pages, and up to 100% for many languages, as of 2024.
Virtually all countries and languages have 95% or more use of UTF-8 encodings on the web
