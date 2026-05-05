# 02 - Project Details (RTCC-O Framework)

## RTCC-O Breakdown

### R - Role
**AI berperan sebagai:** Senior Web Developer & UX Consultant

**Kenapa role ini?**
- Perlu expertise dalam semantic HTML5 dan responsive CSS
- Butuh perspective UX untuk user-friendly portfolio
- Guidance untuk best practices dan clean code

### T - Task
**Main Task:** Membantu membuat portfolio website untuk fresh graduate IT

**Sub-tasks:**
1. Review dan improve content structure
2. Suggest semantic HTML markup
3. Guide responsive CSS implementation
4. Review code untuk best practices
5. Ensure accessibility standards

### C - Context

#### User Profile
- **Status:** Fresh Graduate IT
- **Skills:** Web Development, UI/UX Design, MySQL, Windows Installation
- **Goal:** Landing first job di bidang web development atau IT support
- **Tone:** Professional & Formal

#### Technical Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (minimal)
- **Responsive:** Mobile-first approach
- **Hosting:** GitHub Pages (static site)
- **No frameworks:** Pure HTML/CSS untuk demonstrate fundamentals

#### Existing Assets
- Brainstorm document (design direction, content outline)
- Understanding of target audience (recruiters, hiring managers)
- Clear section requirements (Hero, About, Skills, Projects, Contact)

### C - Constraints

#### MUST HAVE
✅ Semantic HTML5 tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<article>`)
✅ Mobile-first responsive design (320px minimum)
✅ Clean, understandable code (bisa dijelaskan ke recruiter)
✅ No external frameworks (no Bootstrap, Tailwind)
✅ Accessible (proper heading hierarchy, alt texts, ARIA labels jika perlu)
✅ Fast loading (< 2 seconds)

#### MUST NOT
❌ Overly complex JavaScript (keep it simple)
❌ External dependencies (CDN libraries)
❌ Auto-generated code yang tidak dipahami
❌ Plagiarism dari template sites
❌ Unresponsive sections
❌ Broken links atau placeholder content

#### PREFERENCES
- CSS Variables untuk theming
- Flexbox/Grid untuk layouts
- Clean class naming (BEM methodology optional tapi konsisten)
- Comments di code untuk pembelajaran

### O - Output

#### Primary Deliverables
1. **index.html**
   - Semantic, well-structured HTML5
   - Proper meta tags (viewport, description)
   - All sections implemented
   - Valid HTML (W3C compliant)

2. **style.css**
   - Mobile-first media queries
   - CSS Variables untuk colors/spacing
   - Organized sections (reset, variables, base, components, utilities)
   - Clean formatting, proper comments

3. **assets/ folder**
   - Desktop view screenshot (1920x1080)
   - Mobile view screenshot (375x667)
   - Any images used in portfolio

#### Documentation Files
4. **plan/01-brainstorm.md** ✅ (completed)
5. **plan/02-details.md** ✅ (this file)
6. **plan/03-execution.md** (step-by-step process)
7. **plan/04-results.md** (final reflection + screenshots)

#### Live Deployment
8. **GitHub Repository**
   - Clean commit history
   - Proper README with project overview
   - Organized folder structure

9. **GitHub Pages URL**
   - Live, accessible portfolio
   - Tested on mobile dan desktop
   - All links working

## AI Interaction Guidelines

### When Asking for Code
```
Bad Prompt:
"Buatin portfolio website dong"

Good Prompt:
"Saya perlu hero section dengan:
- Full viewport height
- Centered content (name, title, CTA button)
- Background gradient navy → slate
- Mobile responsive
Gunakan semantic HTML dan CSS variables. Explain logic di comments."
```

### When Reviewing Code
```
Ask:
- "Jelaskan kenapa pakai <section> vs <div> di sini?"
- "Apa fungsi CSS property ini dalam responsive design?"
- "Gimana cara media query ini bekerja?"

Goal: UNDERSTAND setiap line of code
```

### When Debugging
```
Share:
- Expected behavior
- Actual behavior
- Code snippet yang bermasalah
- Browser/device info

Don't just copy-paste solutions, ask for explanation!
```

## Quality Checklist

### Code Quality
- [ ] Semantic HTML digunakan dengan benar
- [ ] CSS well-organized dan readable
- [ ] Consistent naming conventions
- [ ] Proper indentation (2 atau 4 spaces)
- [ ] Comments menjelaskan "why" bukan "what"

### Functionality
- [ ] Semua links bekerja
- [ ] Responsive di 320px - 1920px
- [ ] Images load dengan proper sizing
- [ ] Smooth scroll behavior (jika ada)
- [ ] No console errors

### Content
- [ ] No lorem ipsum atau placeholder text
- [ ] Professional language & tone
- [ ] Accurate skill representation
- [ ] Real projects (atau explain clearly jika demo)
- [ ] Working contact methods

### Performance
- [ ] Images optimized (< 200KB each)
- [ ] CSS minification (optional)
- [ ] Load time < 2 seconds
- [ ] No unused CSS/JS

### Accessibility
- [ ] Proper heading hierarchy (h1 → h2 → h3)
- [ ] Alt text untuk semua images
- [ ] Sufficient color contrast (4.5:1 minimum)
- [ ] Keyboard navigable
- [ ] Screen reader friendly

## Expected Timeline

| Phase | Duration | Deliverable |
|-------|----------|-------------|
| Brainstorm | 30 min | 01-brainstorm.md |
| Planning | 30 min | 02-details.md |
| HTML Structure | 1 hour | index.html skeleton |
| CSS Styling | 2 hours | style.css complete |
| Content Writing | 1 hour | All sections filled |
| Testing & Debug | 1 hour | Bug-free portfolio |
| Documentation | 1 hour | 03-execution.md + 04-results.md |
| Deploy | 30 min | Live on GitHub Pages |
| **TOTAL** | **7.5 hours** | Complete portfolio |

## Success Criteria

### Minimum Viable Portfolio (MVP)
✅ All required sections present
✅ Mobile responsive
✅ Clean, understandable code
✅ Professional appearance
✅ Live on GitHub Pages
✅ Complete documentation

### Excellent Portfolio
✅ All MVP criteria
✅ Smooth animations/transitions
✅ Attention to typography details
✅ Perfect accessibility score
✅ Impressive projects showcase
✅ Personal brand clearly communicated

## Next Steps
1. Proceed to execution → `03-execution.md`
2. Build portfolio following RTCC-O guidelines
3. Document each step dengan screenshots
4. Test thoroughly before deployment
5. Complete final results documentation