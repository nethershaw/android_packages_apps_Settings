android_packages_apps_Settings
==============================
My attempt at cherry-picking
>>> http://review.cyanogenmod.org/44675
from cm-10.1

Settings: External GPS Support (1/2)

- Ported feature from CM9
- Fixed string/arrays files
- Removed translation
Patch Set 2:    - Removed random tabs
Patch Set 8:    - Renamed method names to match Android
                  Code Guidelines
Patch Set 9:    - Remove some duplicate codes
                - Fix missing string
                - Fix some formatting issues
Patch Set 10:   - Fix string regression introduced on PS9
Patch Set 11:   - Fix white space error
Patch Set 12:   - Rename some strings to make them better
                  understandable to the user
                - Move string out of cm_arrays.xml
                - Some cleanup
Change-Id: I5590b23a6539ae0a9b2fb8a07eed5fabdf290cbf
