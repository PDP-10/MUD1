# MUD1
Essex MUD1 by Trubshaw and Bartle

MUD.TAP is a DECTape image of MUD from 1984. This has an operational binary of MUD and VALLEY. Restore the tape to a PPN
of [2011,2011] and provding you do not want to make any changes, you can just type RUN MUD

You should create a PPN of [2011,2776] which is the maintainer PPN. When you RUN MUD[2011,2011] from [2011,2776] you can
log into the game with a persona of Richard which is an arch-wiz. This allows you to manage the game before anyone has become a
Wiz.

Alternatively, create you own persona and work up to Wizard. When you reach Wizard level the WIZ MODE password will be revealed
on exit. The WIZ MODE passwaord is hard coded with a simple obsfucation in the source.

Note that personas are PPN specific, so if you create Noob when logged in to [2653,2653} (the MUD guest PPN), you can also create Noob
when logged in to [2011,2011] but they are not the same Noob, even though only one of them can be in game at once. Richard will
only work from [2011,2776].

MUD1.ZIP is the MUD 1986 source files that Richard Bartle donated to Stamford. There are errors in MBOOTS.MAC, TXTCBT.GET, TXTRMS.GET, 
TXTTXT.GET and missing files *.DBA (which can be copied from the MUD tape), POWER.BCL and MUD.MIC. The corrected source files for these
issues is in the master branch.

MUD.ZIP is the source files only extracted from the MUD.TAP tape and packaged up for easy distribution. They are of no real use
if you can process either of the files in the two objects described above and were produced to send to Richadr who didnt have a 
copy of that MUD version.

MUD86.TAP is a simh tape file for a DEC-10 TOPS10 system with executabes and source for the 1986 version of Essex MUD.


Released by Richard Bartle exclusively for not for profit use 
18 May 2020 under GNU General Public Licence version 3
https://www.gnu.org/licenses/gpl-3.0.html

