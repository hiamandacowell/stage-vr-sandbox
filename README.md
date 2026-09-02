# stage-vr-lab

Sandbox for the Hill Auditorium practice space. Experiments live here so that
the working thing stays working.

- **The app** — <https://amandacowell.com/stage-vr/>, from
  [`hiamandacowell.github.io`](https://github.com/hiamandacowell/hiamandacowell.github.io)
  under `stage-vr/`. Nothing in this repo touches it.
- **The lab** — <https://amandacowell.com/stage-vr-lab/>, from here.

Both are served from the same domain, which has one consequence worth knowing:
**they share `localStorage`.** The lab therefore saves its arrangement under
`hill-practice-LAB-v3` rather than the app's `hill-practice-space-v3`, so an
experiment here cannot move the piano in the real one. The unlock word is
shared on purpose; it is the same person.

It says **LAB** on the gate, the start screen and the tab, because the two look
identical from across a room with a phone on your face.

The panoramas are copied rather than borrowed, so this runs on its own from a
folder with no network.

Design notes and the long history live with the app, in `README.txt` alongside
the Documents working copy.

## What it is for right now

Working out whether sheet music can be read in a Google Cardboard viewer, and
if so, what has to exist for a student to get their own music into it.
Cardboard is the target; other headsets are secondary.
