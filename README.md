# HamPiRadio Transceiver

[Join us on Discord](https://discord.com/channels/1224380244056604783/1224380244652327044) 


I will add / update photos on the website in the next days. M

Michael, pictures etc, can be part of the README, but I would suggest that items used for reference, should go in the wiki https://github.com/HamPiRadio/HamPiRadio/wiki because when others get involved and contribute, they won't all have access to your website, that why we use collaborative wikis.

–

#### The Ham Pi Radio Project:
HamPiRadio is a 16 band Amateur Radio receiver and transmitter.  A 'Home Build', so the HAM can buy the bits and construct for themselves.
It is designed to receive on LF, HF and VHF bands and transmit on all HF bands with 100W and on 8, 6 and 4Mtr bands on reduces power.
It is essentially an Analog Transcsiver with all the needed controls available (conventional controls - Knobs!) or single press function buttons, for ease and speed of access control.
The Performance is expected to be among the best (Testing shows it is as good or better than an IC-7300).
Current test results here: https://hampiradio.com/test-results/
Video comparison with other radios: https://hampiradio.com

There essentually 4 PCBs to the design and of course they can be used individually for other projects.  The boards are 1. Radio Board, 2. CPU & Keypad board(s), 3. BandPass Filter Board & 4. PA Board.

#### List of features:
For full and ongoing features see the HamPiRadio website:  https://hampiradio.com/features/

#### Contributing:
For Active 'On The Go' issues please join us here:  HamPiRadio Discord https://discord.com/invite/6k9mv8ME
Contributors / Developers are welcome to this project. We are looking for:
- Compitent RF and Analogue electronic designers to assist with a small number of issues
- Assistance with the mechanical Case design.
- Someone willing to design a 3D plastic Bezel.
- At some point those to do testing further of the RF capability of the transceiver and update the test results (Test euippment will be needed).
- While the software is working really well, there are some 'extra' desirables we have in mind (Such as remote controll over USB, CW paddle (currently 'straight key), a CW decover to text etc).
- 
By opening up this project to others we are looking for 'helpful' and 'active contributions' from others who are keen to get this project flying. We are not so interested in armchair critics or in major re-designing project ideas. The current quest is to polish up this already cool design and get it fully working, reproducible and have others build and use them.
If you are able to report bugs, then please do. Feature requests are encouraged; and any contributions to the documentation/ wiki are welcomed. Why not say ‘Hi!’ in the HamPiRadio Discord https://discord.com/invite/6k9mv8ME 

#### Schematic:
Schematics will be available on this repository. They are in KiCad version 8.0.1 release build


#### Technical Description:
Block diagram? Yes, to follow. M

#### Hardware:
A few sentences about the High Level Design?

#### Operation:
A primary requirement of the project was 'Ease of Use', meaning ease and speed of access to all controls control. No need to wade through menus to find the control you needed in a hurry 2 minutes ago and lost that rare DX!
In any quality receiver it is desirable to vary the gain across the various receiver stages, and have the right filters available at a touch.
The HamPi rotary controls are: AL Gain, IF Gain, AGC Decay, Notch Filter, AF Filter and Noise Blanker (Woodpecker / Static Crash etc).
Keypad buttons cater for full RIT - IRT, ITT and IRTT for split frequency operation. Attenuator and RF Preamp, Mode (CW and SSB), Band Change, SPOT for netting in CW, Keyer functions, Linear Amplifier  delay,
  Power output adjust, Lock dial. There is a Function button to select such as  Wide & Narrow IF Shift, and various other functions and a normally hidden menu for the basic transceiver setup.
Two types of memory...  MW

#### Operating Manual / Instructions:
Will be uploaded to this repositary as a .pdf (Michael, an editable copy should be a goal, as the manual will be refined/ translated.

#### Main components:
Maybe a few words or a line about each? Not essential. The Wiki will be the main place for the information.

BOARDS
1. Radio Board
2. CPU Board
3. Keypad Board
4. BandPass Filter Board
5. PA Board
6. Front Panel Board

7. HamPi Firmware
8. Heatsink Drawing
9. Case Drawings
10. Ancillary Parts BOM


#### Rollout Plan
This is the plan for the HamPiRadio at Michael's end.  The Rollout is a progression of the project as he sees it to get to a comlete MVP / working Transceiver.
1. Manufacture latest CPU + Keypad boards 5 off, SMD and build / test.  For nor use current Front Panel PCBs and drill for the relocation of the LEDs. (Looking for a cool Contributor to desigh a sexi front panel / solks).
2. Suggest Contributers who are also builders start with the new CPU + Keypad + Radio Board, Current produced version. This is then a working on the bench set up of the Receiver / Transmit with out Bandpass or PA boards.
3. Sort the two issues on the Radio Board as detailed on Doscord by myself or preferable with Contributers help.
4. Update the Radio board when 3. is compelete and manufatuture 5 off.
5. Update the BPF and BPF boards for first SMD manufacture. Not a big job as they are already SMD just have been hand placed up to now. Some small changes are desired. Low risk.
6. 'Other' - Case, wrapping up a stable desigh for sharing etc.

#### In operation
What’s it like when it’s in operation/ working?

#### Notes:
Open/ closed source of code. For now the downloadable UF2 firmware will be freely avaidable on git. The firmware works well and is stable. The software source will be reserved, at least for the time being. It will be released on a restricted basis to a limited team of contributers who have the necessary C language skills + Transcsiver skills. There are some desired future software additions to the software sugh as CW IAMBIC, CW decode to text and remove PC control. Are you up to it and keen?

#### Credits & Contributors:
**Michael Wise ZL3AZ** (G0GPX / J87AB St Vincent and the Grenadines) The HamPiRadio is the creation of Michael who has lived North oc Christchurch, New Zealand since 2002.

**Chris Andrew 2E0FRU** Chris is a needed and great encouragement and practical help in making the HamPiRadio a shared and Open-Sourced project.

**Derwyn Williams ZL4SAE/GW4SAE** Now Silent Key. Derwyn (Will) passed peacefully at home in Marton, New Zealand on 9th April 2019. Derwyn assisten me and contributed to the HamPiRadio Radio Board in its earlier forms, and became a close friend. We spoke at least weekly for hours about the design. His website is still up here: https://gw4sae.wordpress.com/ and has many useful contributions. I miss Will a lot. (Michael ZL3AX)

< looking forward to adding other contributers here >




