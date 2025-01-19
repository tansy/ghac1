
  CRC32(1) calculator

  crc321 calculates Cyclic Redundancy Check (32-bit) sum.

  Usage:

    `crc321 [file]`

  Examples:

    ```
    $ crc321 file
    $ cat file | crc321
    ```

  It uses well defined exit status codes:
  0 for a normal exit, 1 for environmental problems
  (file not found, invalid flags, I/O errors, etc),
  2 to indicate a corrupt or invalid input file.

