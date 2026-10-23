# Meta prompt: one-page portfolio for Jubair Ahmad Warisi

This is the design brief the website (`index.html`) was built from. You can reuse it with any AI tool or designer to rebuild or extend the site.

---

## 1. Role and goal

You are a senior web designer and front-end developer. Build a **one-page personal portfolio website** for **Jubair Ahmad Warisi**, a Founding Principal and Islamic education leader from Dhaka, Bangladesh.

**Primary goal:** convince the hiring committee of an **international Islamic school (Cambridge / Edexcel curriculum)** to shortlist him for the **Principal** position.

**Secondary goals:**
- Give recruiters a single link to share (`https://<username>.github.io`).
- Let visitors download the full CV as a PDF in one click.
- Make contacting him effortless (email, phone).

## 2. Audience

- School owners, board members and HR managers of international Islamic schools in Bangladesh and abroad.
- They are busy, scan quickly on phone and desktop, and judge credibility within ~10 seconds.
- They value: leadership proof, numbers, Islamic scholarship, English/Arabic fluency, professionalism.

## 3. Tone and brand

- **Tone:** dignified, trustworthy, calm, modern. Not flashy, not "startup".
- **Feel:** a respected scholar who is also a modern school leader.
- **Colours:** deep Islamic green `#123f35` (primary), warm gold `#b8913a` (accent), cream `#faf7f0` (background), ink `#1f2a27` (text). Match the CV.
- **Typography:** elegant serif for headings (Cormorant Garamond), clean sans-serif for body (Inter), classical Arabic face for Arabic text (Amiri). All from Google Fonts.
- **Motif:** subtle geometric Islamic star pattern (8-point star) at very low opacity in the hero and contact sections. Never busy.
- **Opening touch:** "بسم الله الرحمن الرحيم" above the name.

## 4. Page structure (single page, in this order)

1. **Sticky navigation**: monogram "JAW", links (About, Experience, Education, Skills, Contact), gold "Download CV" button, hamburger menu on mobile.
2. **Hero**: Bismillah, name, Arabic name (زبير أحمد الوارثي), role line "Founding Principal · Islamic Education Leader · Arabic Specialist", 2-line value statement, buttons (Download CV, Contact me), professional photo in a gold arched frame (mihrab shape) with a floating badge.
3. **Impact numbers strip**: 2 academies founded · 11 teachers led · 300+ students taught · 10+ countries · 40+ personal awards.
4. **About**: professional profile paragraph, educational-vision quote card, 4 quick facts (Hafiz of the Quran, Master's-equivalent Dawrah-e-Hadith, 4 fluent languages, ISTP personality).
5. **Experience**: vertical timeline in two groups:
   - *Leadership*: Founding Principal, Maktab Academy (Mar 2026–present, 3 teachers); Founding Principal, An Naseeha Academy online (2023–present, 8 teachers, families in New York, Los Angeles, London, Tokyo, Sydney, Dubai); Dawah Coordinator, Madrasatud Dawah (2023, 6 teams across 6 zones of Dhaka Metropolitan).
   - *Teaching*: Arabic Teacher, An Noor Academy (2024–present); Quran & Islamic Studies Teacher, Deeni Madrasa online (2024–2026, students in Australia, Ireland, Spain, Denmark); Arabic & Islamic Theology Teacher, Jamia Anwarul Ulum, Hazaribagh (2022–2023).
6. **Education & training**: two columns.
   - *Education*: Certificate Course in Arabic, CATTR, University of Dhaka (May–Aug 2026, completed); Takhassus in Dawah, Markazud Dawah Al Islamia (2020–2022, Jayyid Jiddan); Comparative Religion, Jamiatul Ulumil Islamia (2019–2020, Jayyid Jiddan); Dawrah-e-Hadith, Jamiatul Ulumil Islamia (2018–2019, Jayyid Jiddan, government-recognised Master's equivalent); Hifz al-Quran, Jamia Qurania Arabia, Lalbagh (2009, Mumtaz).
   - *Training*: Hasanah Foundation Arabic Language Teacher Training for Non-Native Speakers (40 hours, Sep–Oct 2026); YES Academy 21-Day Self Skill Development (Sep 2026); Deeniyat Teacher's Training, Batch 104 (Jul 2026); YES 21 School & GFDI Happy Life Course, 40th Batch (2026).
7. **Skills**: core-competency chips; language bars (Arabic, English, Urdu fluent; Bangla native; Persian intermediate); digital skills; ISTP personality card with 5 leadership traits; achievements (students won prizes in 1,000+ competitions).
8. **Contact**: headline "Open to Principal roles at international Islamic schools", email, phone, location as large tappable cards, Download CV button.
9. **Footer**: © year, name, back-to-top link.

## 5. Technical requirements

- **One file**: `index.html` with inline CSS and JS. No build step, no framework. Assets in `/assets`.
- **GitHub Pages ready**: relative paths only, works from the repository root.
- **Responsive**: mobile-first; looks perfect at 360px, 768px, 1280px+. No horizontal scrolling.
- **SEO meta tags**: title, description, keywords, author, robots, canonical, theme-color, Open Graph (profile), Twitter card, and JSON-LD `Person` schema.
- **Performance**: no heavy libraries; fonts with `preconnect` and `display=swap`; lazy-load nothing above the fold.
- **Accessibility**: semantic landmarks, skip link, alt text, visible focus states, AA colour contrast, `prefers-reduced-motion` respected.
- **Motion**: gentle fade-up on scroll (IntersectionObserver), nav shadow after scrolling. Nothing distracting.
- **Privacy**: do not publish date of birth or referees' phone numbers on the web page.

## 6. Quality checklist

- Every fact matches the CV. Invent nothing.
- Clear hierarchy: a recruiter should grasp "Founding Principal, 2 academies, 11 teachers, 300+ students" within 5 seconds.
- Download CV works; email and phone links open the mail app / dialler.
- Passes a visual check on desktop and phone.
