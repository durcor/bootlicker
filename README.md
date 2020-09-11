# bootlicker
Easy and dynamic interface to EFI management using efibootmgr

## Dependencies
- Motherboard with UEFI support
- POSIX-capable system (sh, awk, sed)
- efibootmgr

## Usage
```sh
# To list current EFI entries
./bl ls

# To list current EFI entries with extra details
./bl ls all

# To create a new EFI entry
./bl new

# To add all installed kernels as new EFI entries
./bl new all
```
