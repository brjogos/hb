1. Copy the full content of `/SOURCE/RL` from your original CA-Cl*pper
   installation to this directory.

2. *nix users need to convert original filenames to lowercase and EOLs
   to native format, using this command:

   `hbmk2 -sanitize *.PRG`

3. Apply supplied patch to the source using GNU Patch:

   `patch -lNi rl.patch`

4. Build it:

   `hbmk2 rl.hbp`

5. Done.

[vszakats]
