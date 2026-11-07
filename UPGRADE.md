# Random-Required modernization

- jQuery 3.6.4 slim -> 4.0.0
- Bootstrap 4 alpha.6 -> 5.3.8 (latest stable 5.x)
- Tether removed; Bootstrap 5 bundle includes required positioning code
- Font Awesome 4.7.0 -> 7.3.1
- Fixed invalid jQuery event strings (`change, keyup` -> `change keyup`)
- Replaced jQuery Deferred/pipe flow with native Promise chaining
- Updated clipboard copy to use the Clipboard API when available
- Updated generator worker syntax to modern JavaScript

The project remains a static browser app and can be deployed directly to Vercel.
