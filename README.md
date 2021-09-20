# cbrXz - cbr unpacker
cbrXz.py copies a tree, replacing CBRs with CBZs as it goes.

### usage
```
cbrXz.py source destination
```
Crawls *source* and copies the books to *destination*, converting rars to zips.

### options
```bash
--rar-only, -R
```
Copies only rar files.

```bash
--replace, --forced, -F
```
Enables the repack process to replace existing files. It'll nuke everything under *destination* if you screw up. You've been warned.

```bash
--dry-run, -N
```
disable all actions that actually DO anything. This is supposed to be safe...

```bash
--verbose, -V
```
be more noisy than usual, but less than debug output

```bash
--debugging
```
activate debug mode.
