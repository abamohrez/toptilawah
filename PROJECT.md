# Project: @toptilawah — Daily Tweet Assistant

## Project Overview
A web application that helps the @toptilawah account on X (Twitter) prepare and publish daily tweets containing a Quranic verse, its Tafsir (exegesis) explanation, and a recitation video.

**The app interface is in Arabic. All our development conversations are in English.**

## Current Status
- **Version:** v1.3
- **Type:** Single HTML file (Single Page App)
- **Hosting:** GitHub Pages (free)
- **App Language:** Arabic
- **Last Updated:** May 2026

## How to Work With Claude on This Project
At the start of every new conversation, copy and paste the full content of this PROJECT.md file, then describe what you want. Example:
> "Here is my project file: [paste content] — I want to add a feature that does X..."

This gives Claude full context since it has no memory between conversations.

---

## Features Already Built ✅
- [x] Surah and Ayah selector (all 114 Surahs)
- [x] Six Tafsirs: Ibn Ashur, Ibn Kathir, Al-Tabari, Al-Saadi, Al-Qurtubi, Al-Baghawi
- [x] AI-generated Tafsir text (via Claude API)
- [x] Auto-drafted tweet in Arabic
- [x] Tweet preview styled like X (Twitter)
- [x] PDF library for Ibn Ashur's Tafsir (upload up to 90 volumes)
- [x] Built-in video editor (trim and export)
- [x] Search across 8 Quran recitation accounts on X
- [x] Search links for TikTok and YouTube
- [x] Add/remove Quran reciters
- [x] Add/remove X accounts
- [x] Published verses history log
- [x] Verse suggestions by topic
- [x] Settings saved locally (localStorage)

## Features Planned / To Be Built 🔧
- [ ] Improve Tafsir accuracy using uploaded PDF files
- [ ] Direct X (Twitter) API integration for auto-posting
- [ ] Daily reminder notifications
- [ ] Convert to mobile app (PWA first, then native app)
- [ ] Tweet engagement analytics

---

## Project Files
| File | Description |
|------|-------------|
| `index.html` | The full application |
| `PROJECT.md` | This file — project memory and documentation |

---

## Version History
| Version | Date | Changes |
|---------|------|---------|
| v1.0 | May 2026 | First version — core functionality |
| v1.1 | May 2026 | Added 6 Tafsirs + built-in video editor |
| v1.2 | May 2026 | Fixed Surah dropdown bug + PDF manager |
| v1.3 | May 2026 | Added X search tab + 8 recitation accounts |

---

## X Recitation Accounts (Built Into App)
@Quraan_777 | @Qurantilawat1 | @agmalaltilawat | @_listen2quran_
@abdullah11AA | @QuranRecite24 | @abdllhfrhan | @Mazameer

---

## Key Technical Decisions
- **Single HTML file:** Easier to maintain, upload, and share
- **Claude API:** Called directly from the browser for Tafsir generation and tweet drafting
- **localStorage:** Used for saving settings, reciters list, and history
- **sessionStorage:** Used for temporarily storing extracted PDF text
- **No backend server needed:** Everything runs in the browser

---

## Tafsirs Supported
1. Ibn Ashur — Al-Tahrir wa Al-Tanwir (التحرير والتنوير) ← Primary
2. Ibn Kathir (تفسير ابن كثير)
3. Al-Tabari — Jami' al-Bayan (جامع البيان)
4. Al-Saadi — Taysir al-Karim al-Rahman (تيسير الكريم الرحمن)
5. Al-Qurtubi — Al-Jami' li-Ahkam al-Quran (الجامع لأحكام القرآن)
6. Al-Baghawi — Ma'alim al-Tanzil (معالم التنزيل)

---

## Ibn Ashur PDF Library
- Source: archive.org/details/tahrer_tanwer
- Format: 30 volumes (PDF)
- Total size: ~225 MB
- Download method: Torrent via qBittorrent (recommended)
- Torrent file: archive.org/download/tahrer_tanwer/tahrer_tanwer_archive.torrent
- After downloading, upload PDFs in the app under: Settings → PDF Library

---

## Roadmap to Mobile App
1. ✅ **Now:** HTML file hosted on GitHub Pages
2. 🔧 **Next:** PWA (Progressive Web App) — adds "Install" button on mobile, works offline
3. 🔮 **Future:** React Native or Flutter — publish on App Store & Google Play

---

## Notes & Decisions Log
- 2026-05: Decided to keep app interface in Arabic, development in English
- 2026-05: User prefers GitHub Pages over Netlify for hosting
- 2026-05: Video trimming uses Canvas + MediaRecorder API (browser-native, no server)
- 2026-05: PDF text extraction uses PDF.js loaded from CDN
