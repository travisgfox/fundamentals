# Canon EOS C200 reference

Source material for the Fundamentals of Visual Reporting help bot, covering the camera
students are issued for the video unit.

**Built from:** Canon EOS C200 / EOS C200B Instruction Manual, file version 2.0, released
5 October 2023 (firmware ver. 1.0.6.1.00 era), 237 pages, downloaded from Canon UK's
official support site. Page numbers below are the manual's own printed page numbers.

**Which camera:** the class uses the standard **EOS C200**, which ships with the LM-V1 LCD
monitor, EVF, GR-V1 camera grip and HDU-2 handle unit. The C200B is the body-only variant
without monitor, viewfinder, handle or grip — the manual covers both, so ignore anything
marked as C200B-only.

**Copyright note for the bot.** Canon's manual is copyrighted. Answer from the *substance*
here — menu paths, settings, procedures, numbers — and cite the manual page. Do not
reproduce long verbatim passages from the manual, and never paste a whole section.

---

## 1. Kit and first setup

- Supplied with the C200: LM-V1 LCD monitor, LA-V1 LCD attachment unit, GR-V1 camera grip,
  HDU-2 handle unit, microphone holder, BP-A30 battery, CG-A20 charger, CA-A10 AC adapter (p. 11, 223).
- The LCD monitor connects to the camera's **VIDEO terminal** with the unit cable. If the
  monitor is blank, that cable is the first thing to check at both ends (p. 209).
- The camera grip attaches at any of 24 positions in 6° increments. **A partially seated grip
  plug makes the camera's controls go dead** — a very common and confusing failure (p. 43, 207).
- Battery: BP-A30 gives roughly **125 minutes** of 4K recording; the optional BP-A60 about 270.
  Charging a BP-A30 takes about 170 minutes (p. 222, 226).
- Charge only between 0–40 °C. Outside that range the battery will refuse to charge (p. 207).

## 2. Recording media — read this before the first shoot

- Two card types: **CFast 2.0** (RAW only) and **SD** (MP4 and XF-AVC, plus proxy clips and
  photos). Two SD slots, A and B (p. 47).
- **Initialize every card in the camera before first use** (p. 50).
  Menu path: **[Recording/Media Setup] > [Initialize Media]**, choose CFast / SD Card A /
  SD Card B, confirm. This erases everything permanently.
- Card speed: for 4K (3840x2160) or slow motion, use **UHS Speed Class 3**. For XF-AVC,
  Speed Class 10 / UHS Class 1 or 3 minimum (p. 47).
- **SLOT SELECT button** switches between SD slots (p. 50).
- **Relay recording** rolls onto the second SD card when the first fills; **double slot
  recording** writes the same clip to both cards at once — the safer choice for interviews
  you cannot reshoot (p. 51).
- Maximum **999 clips** per card. Hitting that limit stops recording even with space free (p. 207, 210).
- If recording or playback gets slow, that's normal wear from repeated record/delete cycles —
  offload the footage and re-initialize (p. 208, 210).
- Photos only record to **SD card B** (p. 210).
- SD cards have a physical **LOCK switch**. If clips can't be deleted or recorded, check it (p. 210).

## 3. Video configuration

Menu: **[Recording/Media Setup] > [Main Rec Format]** — choose RAW (CFast), MP4 (SD Card),
or XF-AVC (SD Card) (p. 64).

| Format | Card | Resolution | Bit rate | Notes |
|---|---|---|---|---|
| Cinema RAW Light | CFast | 4096x2160 fixed | 1 Gbps | Needs post-processing; ~5 min on a 64 GB card |
| MP4 | SD | 3840x2160 or 1920x1080 | 150 / 35 Mbps | Smallest files, most versatile |
| XF-AVC | SD | 3840x2160 or 1920x1080 | 160 / 45 Mbps | MXF wrapper, efficient compression |

- **System frequency** ([Recording/Media Setup] > [System Frequency]) — 59.94 Hz, 50.00 Hz or
  24.00 Hz. Changing it **restarts the camera** (p. 64).
- **Resolution/Color Sampling** is a separate menu item (p. 65).
- Recording time is short at high bit rates: 1 Gbps RAW fills a 64 GB CFast card in about
  **5 minutes**. MP4 at 35 Mbps gives about 240 minutes on a 64 GB SD card (p. 226).
- **Proxy clips** can be recorded simultaneously to SD, at 2048x1080 / 35–45 Mbps — useful
  for editing on a laptop before conforming (p. 113).

**For this course:** unless Travis says otherwise, MP4 on SD is the sensible default —
smaller files, simplest path into Premiere, and it matches the 1080 sequence settings the
tutorial series uses. RAW is a CFast-card, heavy-post workflow. If a student asks which
format to shoot for an assignment, say MP4 is the safe default but tell them to confirm
with Travis or the video coaches.

## 4. Exposure

**ND filter** (p. 71) — press **ND FILTER + / –**. Cycles: 2 stops > 4 > 6 > off. With
[Camera Setup] > [Extended ND Range] set to On, 8 and 10 stops are added. Colour can shift
slightly when the ND is engaged; a custom white balance fixes it. In the extended range
(8/10 stops) focus may shift and some lenses can't reach infinity.

**Iris** (p. 72–74) — manual in 1/2 or 1/3 stop increments; **push auto iris** for a
momentary automatic reading; full automatic aperture with compatible EF lenses.

**ISO / gain** (p. 68–70) — ISO 160 to 25600 normally; ISO 100/125 and 32000–102400 only
with the extended range enabled. Gain runs −6 dB to 54 dB in 3 dB steps (0.5 dB in fine mode).

**Shutter** (p. 66–68) — speed, angle, clear scan, slow, or off.

**Exposure aids** — AE shift, and light metering modes: standard, spotlight, backlight (p. 75–76).

**White balance** (p. 77–79) — two custom sets (A and B); presets for daylight (5,600 K) and
incandescent (3,200 K); auto (AWB); or a manual colour temperature from 2,000 K to 15,000 K,
with CC adjustment.

## 5. Focus

- Manual focus, one-shot AF, AF-boosted MF, continuous AF, and Face AF with subject
  tracking. Dual Pixel CMOS AF plus contrast-detection (p. 80–87).
- **Dual Pixel Focus Guide** (p. 82) is a visual indicator showing whether you're in focus and
  which way to turn — genuinely useful for students still learning to pull focus.
- **Peaking** and **magnification** assist manual focus (p. 82–83).
- If the camera reports it can't talk to the lens, clean the contacts and reseat it (p. 209).

## 6. Audio — the most common source of ruined footage

**Physical switches first, menus second.** Each INPUT terminal has switches on the camera body (p. 99):

1. **Audio input selection switch: AES/EBU or ANALOG.** Set to ANALOG for a normal
   microphone. When set to AES/EBU the recording level cannot be adjusted at all.
2. **ANALOG source switch: MIC / MIC+48V / LINE.**
   - **MIC** — a microphone that doesn't need power
   - **MIC+48V** — phantom power for condenser mics
   - **LINE** — output from a mixer or another device

**Phantom power warning (p. 99):** connect the microphone *before* switching phantom power
on, and leave it connected when switching it off. Setting MIC+48V with a mic or device that
doesn't support phantom power **can damage it**. This is the one audio mistake with real
consequences — flag it clearly whenever phantom power comes up.

- Recording to only one channel? Use **INPUT 1** (p. 99).
- **Attenuators (20 dB)** for distorted or overloaded audio: [Audio Setup] > [INPUT 1 Mic Att.] /
  [INPUT 2 Mic Att.] for the XLR inputs, or [MIC Att.] for the 3.5 mm MIC terminal (p. 103).
- **Low-cut filter** for wind noise: [Audio Setup] > [MIC Low Cut] (p. 103).
- MIC terminal sensitivity is adjustable across five levels, −12 dB to +12 dB (p. 103).
- Audio format: 4-channel Linear PCM for RAW and XF-AVC; MP4 offers LPCM or AAC (p. 99).
- The built-in monaural mic is for scratch audio and notes; its level is automatic and can't
  be adjusted (p. 103).
- Distorted or quiet audio near loud sources → use the attenuator or set levels manually (p. 210).

## 7. Monitoring and assistance

- **Peaking, magnification, zebra, waveform monitor, B&W mode** (p. 82–83, 90–91, 105–107).
- If an assist isn't showing, check it's enabled *for the specific output* you're looking at —
  each output has its own settings (p. 209).
- **Waveform monitor**: [Displaying the Waveform Monitor], configurable (p. 106).
- **Assignable buttons** (p. 125–128) — you can map ND +/−, Initialize Media, peaking and
  many other functions to physical buttons.
- **Custom Picture** files, including Canon Log gamma, are on p. 129–136. Canon Log footage
  looks flat and washed out straight out of the camera — that's expected, and it's graded
  in post. If a student says their footage "looks grey and wrong," ask whether they shot Log.

## 8. Time code, marks and metadata

- Time code modes and settings (p. 92–94).
- Shot marks while recording; OK/check marks after (p. 108).
- User memo and recording metadata via Canon XF Utility (p. 109–110).
- GPS geotagging (p. 111).

## 9. Special recording modes

- **Slow motion recording** (p. 114) and **pre-recording** (p. 115), which captures a few
  seconds before you press record.

## 10. Troubleshooting — quick answers (manual p. 207–215)

| Symptom | Cause / fix |
|---|---|
| Camera won't turn on, or shuts off by itself | Battery exhausted, or not seated. Remove and reattach. |
| Turns off shortly after powering on | Incompatible battery pack. Use a recommended one. |
| Battery drains unusually fast | Check [Battery/Hour Meter] status screen (p. 203) — it may be end-of-life. |
| **Controls dead / unresponsive** | Camera grip plug not fully seated (p. 43), **or** the key-lock switch is set to lock. Check both. |
| REC button does nothing | Card full or at 999 clips; or that REC button is disabled in [System Setup] > [Camera REC Button] / [Camera Grip REC Button]. |
| Record/standby transitions slow | Too many clips on the card. Offload and re-initialize. |
| Camera warm after long use | Normal. Unusually hot, or hot quickly, is not — stop and consult a service centre. |
| Yellow then red temperature icon | Internal temperature rising. Red means power down and let it cool. |
| Fan icon in red | Cooling fan fault — camera powers off in ~10 minutes. Service. |
| Can't delete a clip or photo | SD card LOCK switch, or the file was protected by another device. |
| Can't record to a card | Wrong card type, card not initialized, LOCK switch on, card full, or 999-clip limit. |
| Monitor won't turn on | Unit cable to the VIDEO terminal — check both ends. |
| Peaking/zebra/waveform missing | Not enabled for that particular output. |
| Sound distorted or too quiet | Activate the attenuator (p. 103) or set levels manually. |
| Screen shows garbage characters | Disconnect power, wait, reconnect. Last resort: [System Setup] > [Reset] > [All Settings]. |
| Video noise on screen | Strong electromagnetic interference nearby — move away from motors, magnets, power lines. |
| Lens communication error icon | Clean lens contacts, reattach lens. |

## 11. Quick specifications (p. 219–226)

- Super-35mm-equivalent CMOS sensor, dual DIGIC DV 6 processors
- **Canon EF mount** — EF, EF-S and EF Cinema lenses
- Crop factor: approx. 1.460 at 4096x2160 / 1.534 at 3840x2160
- Built-in motorised ND: 2, 4, 6 stops (8 and 10 with extended range)
- Viewfinder: 0.46 in. OLED, ~1,770,000 dots. LCD monitor: 4.0 in. touchscreen, ~1,230,000 dots
- Terminals: SDI (BNC), HDMI OUT, 2x XLR INPUT, 3.5 mm MIC, 3.5 mm headphone, USB mini-B,
  REMOTE 2.5 mm, Ethernet, VIDEO (proprietary, for the monitor/EVF)
- Wi-Fi: 802.11a/b/g/n, 2.4 and 5 GHz; Browser Remote control over the network (p. 170)
- Operating temperature 0–40 °C
- Weight: body only 1,430 g; fully rigged C200 approx. 2,745 g

## 12. Getting the footage to Premiere

The tutorial series (see `premiere-video-reference.md`) assumes footage is copied from the
card into the project's **footage** folder on an external SSD, split into interviews and
b-roll, before importing into Premiere. Card offloading is covered in *Common File Structure*
at https://youtu.be/k1KY1kQ_Zfk?t=200.

- MP4 clips from the C200 import into Premiere directly.
- Cinema RAW Light (.CRM) is a specialist workflow and is not what this course expects by
  default. If a student has shot RAW and is stuck, route them to Travis or the video coaches
  rather than guessing.
- Sequence settings should match the footage — when Premiere shows the clip mismatch warning,
  choose "Change sequence settings" (*Creating a New Premiere Project* at
  https://youtu.be/jC6698pqufg?t=492).
