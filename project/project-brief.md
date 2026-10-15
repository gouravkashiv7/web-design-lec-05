# Project 1: Your First Complete Website

**Lecture 5 · HTML Mini Project + Code Review**
**Build time:** 70 minutes in class · **Due:** before Lecture 6
**Rules:** HTML only, no CSS. Type the code; don't paste it.

---

## 1. What you are building

A **four-page website** about a real place you know. It uses everything from Lectures 2–4.

Pick **one** topic:

- Your college (for example, JEC Kukas)
- A local business: a shop, café or coaching centre
- A club or society you are part of

Every page has the same **header, nav and footer**. Only the `<main>` changes.

## 2. Start from the starter folder

Copy `project/starter/` out of this repo and rename it `yourname-project-1`. All four pages already have:

- the HTML skeleton (`DOCTYPE`, `html lang`, `meta charset`, `title`)
- the shared header, nav and footer
- `TODO` comments that tell you what to add

Replace every `Site Name` with your topic's name. Delete each `TODO` comment once it's done.

```
yourname-project-1/
├── index.html
├── about.html
├── courses.html
├── contact.html
├── images/
└── README.md
```

## 3. What each page must have

| Page | Must include | Lecture |
|---|---|---|
| `index.html` | One `h1`, a welcome paragraph, a hero image with alt text, links to every page | 2, 3 |
| `about.html` | At least two `section`s, each with its own `h2`, and at least one image | 2, 3, 4 |
| `courses.html` | A table with `caption`, `thead`, `tbody` and `th` cells: 3+ columns, 4+ rows | 3 |
| `contact.html` | Address, an email link, a phone link, and a form with labels, correct types and `required` | 2, 4 |
| **Every page** | `header`, `nav`, `main`, `footer`; same nav; one `h1`; headings in order | 3, 4 |

Not running a college? Rename `courses.html` to `services.html` or `menu.html` and change the nav on **all four** pages.

## 4. Build plan, with checkpoints

Raise your hand at each **checkpoint**. The trainer checks it before you move on.

| Time | Step | Done when | Checkpoint |
|---|---|---|---|
| 0–20 | **Plan** on paper: topic, content for each page, folder tree | You can say what goes on each page | ✋ Show your plan |
| 20–35 | **Shell**: rename `Site Name`, add your logo | All four pages open and the nav works | ✋ Click all 16 nav links |
| 35–55 | **Home and About**: headings, paragraphs, images | Every image shows and has alt text | |
| 55–75 | **Courses and Contact**: the table and the form | You can fill the form with the keyboard only | ✋ Show the table and form |
| 75–85 | **Test**: click every link, check every image, Tab through every page | No 404s in the Network panel | |
| 85–90 | **Validate** every page at [validator.w3.org](https://validator.w3.org/#validate_by_upload) | Zero errors on all four pages | ✋ Show four green results |

## 5. Stuck? Do this before asking

1. **Say it out loud:** "I expected ___ but I see ___."
2. **Inspect:** right-click → Inspect. Is the element where you think it is?
3. **Image or page missing?** DevTools → Network → refresh → look for a red **404**. Compare the URL with your file name: capitals, spelling, folder.
4. **Label not working?** Its `for` must match the input's `id` exactly.
5. **Change one thing, save, refresh.**
6. Still stuck after 5 minutes? Ask a neighbour, then the trainer. Bring your "expected vs actual" sentence.

## 6. Definition of done

Your project is finished when **every** box is ticked:

- [ ] Every page validates with zero errors
- [ ] The nav works from every page (16 clicks)
- [ ] Every image has suitable alt text (`alt=""` only if it's purely decorative)
- [ ] One `h1` per page, and headings never skip a level
- [ ] `header`, `nav`, `main`, `footer` on every page
- [ ] Contact form: every field has a label, the right `type`, and `required` where needed
- [ ] Course table: `caption` and `th` header cells
- [ ] File names are lowercase with no spaces
- [ ] `README.md` answers: what is it, what's inside, how to open it

**Stretch goals:** an "On this page" list of same-page links on About; a `tfoot` row in the table; checking every page's keyboard focus.

## 7. In class after building

### Bug injection (15 min)
The trainer will secretly break a few things in your project. Find them using **only** DevTools and the debugging loop. Log every bug:

| Expected | Actual | Evidence | Cause | Fix |
|---|---|---|---|---|
| Hero image shows | Empty box with alt text | Network: 404 for `images/Hero.jpg` | File is `hero.jpg` | Fixed the case in `src` |
| | | | | |

### Peer review (15 min)
Swap laptops. Check your partner's project against these seven items, then leave **3–5 comments**. Each comment names the line, the impact and a fix.

1. Semantic structure: landmarks used? headings in order?
2. Naming: lowercase files, no spaces, clear ids?
3. Indentation: can you see the nesting at a glance?
4. Duplication: is the nav identical on every page?
5. Accessibility: labels, keyboard access?
6. Broken links: any 404s?
7. Missing alt text: every `img` has `alt`?

The author marks each comment **Accept** or **Reject**, with a reason.

### AI review (optional)
Prompt: *"Review my HTML as a senior developer. Rank issues by severity. Don't rewrite the code."*
Mark every finding **Accept** or **Reject**, with a reason you checked yourself.

## 8. What to submit

1. Your `yourname-project-1/` folder, zipped
2. `README.md` inside it
3. Your bug log
4. Your review notes: each comment you received and what you did about it

## 9. How it is marked (20 marks)

| Area | Marks | Full marks means |
|---|---|---|
| Structure and semantics | 4 | Landmarks on every page, one `h1`, headings in order, clean indentation |
| Content | 3 | All four pages complete, with real content about your topic |
| Links and images | 3 | Nav identical and working, alt text on every image, no 404s |
| Table | 3 | `caption`, `thead`, `tbody`, `th` with `scope`, 4+ rows |
| Form | 4 | Every field labelled, correct types, `required`, usable by keyboard only |
| README and validation | 3 | README answers all three questions; zero validator errors |

**Example of a finished project:** `class-code/jec-kukas-site/` in this repo. Look at it **after** you've built your own, not before.
