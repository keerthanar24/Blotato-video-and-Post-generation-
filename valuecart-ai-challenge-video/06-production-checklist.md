# Part 6 · Production Checklist & Delivery

### Build order (fastest path)
1. Paste **Block A** (`03-heygen-paste-ready.md`) into the HeyGen prompt window → generate draft.
2. Generate **IMG-01, 02, 03, 11** first — they carry 4 of the 6 scenes.
3. Generate **CLIP 01, 07, 08** (ignition, trophy, walk-in) — the three that add the most production value.
4. Replace HeyGen's stock backgrounds with your images/clips scene by scene.
5. Type all copy as **HeyGen text layers** (never baked into images) so it stays sharp and editable.
6. Add transitions per the map in `02-master-script.md`, then the music bed.
7. Export 16:9 → then duplicate the project and re-run **Block C** for the 9:16 cut.

### Pre-export QA
- [ ] **No date appears anywhere** — spoken, on screen, in captions, or inside a generated image
- [ ] Runtime is **40.0s or under**
- [ ] Both ₹2,00,000 figures are correct and formatted Indian-style (`2,00,000`, not `200,000`)
- [ ] "Tech" and "Non-Tech" both appear — neither team is implied to be excluded
- [ ] The note "All participating team members must present their AI tool" is legible for ≥2s
- [ ] Captions never overlap the avatar or the bottom 15% safe area
- [ ] Ends on the lit Valuecart logo — **no fade to black**
- [ ] Audio peaks ≤ −3 dBFS; VO sits ~8 dB above the music bed

### Export settings
| | 16:9 | 9:16 |
|---|---|---|
| Resolution | 1920×1080 | 1080×1920 |
| FPS | 30 | 30 |
| Codec | H.264, ~10 Mbps | H.264, ~8 Mbps |
| Audio | AAC 192 kbps stereo | AAC 192 kbps stereo |
| File | `valuecart-ai-agent-challenge-16x9.mp4` | `valuecart-ai-agent-challenge-9x16.mp4` |

### Distribution copy (date-free)

**Teams / internal channel**
> ⚡ Update on the **AI Agent Building Challenge** — final presentations have been rescheduled so every team gets a smoother run. The new presentation schedule is out. Tech and Non-Tech present on the same day, to all team members. Come ready to show your AI tool: time saved, cost cut, and the AI methods behind it. 🏆 ₹2,00,000 for Tech · ₹2,00,000 for Non-Tech. Every participating member presents — bring your best ideas. Let's showcase our innovations and shape our future together!

**WhatsApp / short**
> 🤖 AI Agent Building Challenge — presentations rescheduled, new schedule is out. Tech + Non-Tech, same day. ₹2,00,000 + ₹2,00,000 on the table. Judged on time saved, cost saved, and AI innovation. Bring your best build 🚀

**Email subject lines**
- `Update: AI Agent Building Challenge presentations rescheduled`
- `New presentation schedule — AI Agent Building Challenge`
- `₹4,00,000 in prizes. New schedule. Bring your AI tool.`
