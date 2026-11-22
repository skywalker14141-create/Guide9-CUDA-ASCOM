Guide 9.1 with CUDA, ASCOM, and N.I.N.A.

INSTALLATION

This package requires the January 1, 2019 Windows build of Guide 9.1.
Close Guide and the package tools. Back up guide.dat and any files you
will replace, especially asc_link.dll. Extract the ZIP alongside
guide9.exe, then launch Guide9-CUDA.exe from that folder.

CUDA

Enable “Use MPCORB” in Guide. The engine accelerates asteroid indexing
on NVIDIA GPUs compatible with sm_86. Guide automatically falls back
to the CPU when CUDA is unavailable. Tested on a GeForce RTX 2050.

ASCOM

Install the ASCOM Platform and a mount driver that supports 32-bit
clients. In guide.dat, add SCOPE_EPOCH=2000 or update the existing value.
If asc_link.ini specifies CoordinateMode, set it to J2000. In Guide9-CUDA,
open Settings → Scope Control, select ASCOM Scope, confirm, then select
and configure your driver. Guide9-ASCOM.exe is an optional diagnostic tool
for testing the connection and reading mount position. ASCOM was tested
with a simulator.

N.I.N.A. BRIDGE

1. Launch Guide9-NINA.exe and leave its window open or minimized.
2. In N.I.N.A. → Options → Equipment → Planetarium, select Cartes du Ciel,
   host localhost, port 3293. You only need to set this once. The bridge
   uses this entry without running Cartes du Ciel.
3. Center the target in Guide 9. Keep one Guide window open, with Earth
   as the observing planet and J2000 as the coordinate format.
4. In the N.I.N.A. Framing Assistant, click the pin next to Coordinates.
   The chart center appears under the name “Centre Guide 9.”

The bridge imports the live chart center without a .mar file or a mount
move. It recognizes the January 1, 2019 Guide 9.1 build and the included
Guide9-CUDA build. The connection stays on your PC. Tested in N.I.N.A.
3.3 Nightly #069.

SHA-256 of the original guide9.exe
32893608e82b014c84f9a3487263ec345f3611b75d5b0f786f7a878fbb047c9d
