# Guitar Hero 80s for Xbox 360

**Welcome to the Future of GH80s!!!**

## Background
GH Rocks the 80s was an underappreciated PS2 exclusive Guitar Hero entry. It had unique character models and venues that never made their way over to Xbox. But what if they did? Thanks to tooling (superfreq), and knowledge advancements, both are now possible on real Xbox 360.

## Installation
- GH80s x360 is in PRE-ALPHA, so the install process is *subject to change*. Currently, there are 2 flavors of GH80s x360: PS2 and Xbox 360.

### Xbox 360
- GH80s x360 for Xbox 360 WILL require the following:
  - Python
  - Access to a CMD prompt
  - A "legally" acquired copy of stock GH2 for the Xbox 360.
- **Installation Steps:**
  1. ENSURE YOUR COPY OF GH2 IS IN A RAW-FILE FORMAT (Refer to the picture below) ![dependencies/STOCK GH2 360 FOLDER.png]
  2. Take your GH2 Raw Files and Place them within `Guitar-Hero-II-Deluxe-Unified\platform\xbox` (it should look like the picture below, DO NOT DELETE ANYTHING ALREADY IN THE FOLDER) ![dependencies/360 STEP 2.png]
  3. Once it is installed, locate the `scripts` folder in the root of the Repository, in this folder run `build_xbox.bat`. A CMD prompt will now open.
  4. Upon completion of the creation of the DX patch, a new folder called `out` should have opened. You now have officially survived the process of creating your very own copy of GH80s x360 for the Xbox 360! Congrats!
  5. Now here is the easy part, you remember that copy of stock GH2 you legally acquired? Well, make a copy of those files, and in this new copy of GH2, simply drag the newly created `GEN` and `default.xex` files/folders (for those who prefer their GH2 with overscan, you can rename `default no overscan.xex` to default.xex after getting rid of the OG default.xex) over to your copy of stock GH2.
  6. You have officially created your own GH80s x360 copy. Now you can use this copy of GH80s x360 on any platform where 360 Games can be run.
