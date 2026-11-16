# CoreFour

Four-bar core loop desk for bedroom producers and AI-music finishers.

Tracks stall because the pocket never locks. CoreFour writes four live-instrument bars that hold the groove so you can finish the song around it.

Live chairs only: FluidR3 piano, nylon, upright, kit (samples pinned from PreEight@d58301e4a494555f411a2afbc448b724136eee76).

Distinct from TagFour (last-line end tag), ModEight (last-chorus key change), LiftTwo (pre-hook lift), PreEight, AfterHook, EndEight, LastHook.

## Form

4-bar core loop (extendable). User's BPM and key.

## Play

- Play the loop
- Change recipe / BPM / key while playing — heard within one bar
- Export WAV (48 kHz, 16-bit stereo for MVP, exact length, first transient at sample 0)
- Export MIDI (stub for MVP; WAV is primary)

## Pricing recommendation

One-time $19 on Gumroad (or Lemon Squeezy). This is a desk, not a recurring studio. Sell next to other WorkinWithAI finishing tools. Free to use; support the line if it ships your tracks.

## Stack

Static HTML/CSS/JS. Deploy on Vercel team `release-forge`.

## Audio engine

Follows WorkinWithAI rules: lookahead scheduler on AudioContext clock, live state, OfflineAudioContext exports, pinned samples, no @main.
