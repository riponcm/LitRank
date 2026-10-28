# Privacy Policy

**LitRank**
Effective October 27, 2026 · Applies to the Chrome, Edge and Firefox extensions, version 1.9.0 and later

---

## The short version

**LitRank has no server.** There is no account, no login, no sync service and no analytics. Nothing you search for, read, or save is transmitted to us, because there is nowhere for it to go. We could not see your reading list, or your search history, if we wanted to.

Everything the extension needs to put a quartile badge on a search result is already inside the extension when you install it. The lookup happens on your own machine.

Some features read pages beyond Google Scholar: the **search log**, **Log this search**, **Save to LitRank**, and **journal ranks on database results**. Each is off until you turn it on or press a button, and each is described in full below.

---

## What LitRank stores

| What | Where | Who can read it |
|---|---|---|
| Papers you save, and the folders you file them under | Your browser's local extension storage, on your device | You, and any extension-inspection tool you run yourself |
| **If you turn on the search log, or use Log this search:** for each search, the database's or website's name, the search text, the filters applied, the number of results, the address of the results page, the date, and the folder it was filed under | The same | The same |
| Which databases and websites the log is turned on for, whether journal ranks are shown on them, and any library address you add | The same | The same |
| Your filter and sort preferences on Google Scholar | Your browser's extension storage; if you have turned on your browser's own sync, your browser copies these few settings between your signed-in devices (see below) | The same |
| A pointer to a sync folder, if you choose one | The same | The same |

That is the complete list. There is no hidden identifier, no install ID, no fingerprint and no usage counter.

The search log **never stores the articles a database returns**, only what you searched for and how many results came back.

If you have enabled your browser's own extension-data sync (a browser feature, not ours), your browser may replicate this storage across your signed-in devices under **its** privacy policy, not this one.

---

## What LitRank reads, and when

LitRank reads a web page only in these five cases, and in each the choice is yours.

### 1. Google Scholar

On Google Scholar results, profile and Labs pages it adds badges and the filter bar. This is the extension's original purpose.

On an author's profile, if you press **Analyse this author**, LitRank loads the rest of that profile's publication list (see "Load more" below) and summarises it in a panel above the list: Scholar's own citation figures and chart from the page, journal quartiles, top papers, title keywords and subject areas. It is worked out in your browser from what the profile shows. Nothing is stored, and nothing is sent anywhere.

### 2. The search log (off until you turn it on)

If you turn the search log on for a database, LitRank reads that database's **results page** while you look at it, to record the search text, the filters, the result count and the date, so you can report them when you write a review.

- It is **off for every database until you turn it on, one at a time**, from the LitRank library.
- Turning on a database other than Google Scholar makes your **browser** ask whether to allow LitRank on that site. You can say no, and nothing is read. The request names only that database's addresses, never "all sites".
- If you reach a database through your university library's proxy, you can add the library's address so LitRank can read those pages too. Again your browser asks first, and the request names exact hostnames.
- It reads the page you are already looking at. It **never runs a search, clicks, scrolls or downloads** for you.
- You can pause it, remove its access, or delete every row at any time from the library. Removing access also withdraws the browser's permission.
- What it records is stored on your device only. See "What LitRank stores".

### 3. Log this search (only when you ask), and publisher websites (only if you turn them on)

When you right-click a search results page and choose **Log this search**, or press its shortcut (Alt+Shift+K by default), LitRank reads that one page's address and what it shows about the search — the search text, the filters and the result count — and adds the search to your log. It can read the page only after you do this, only in that tab. Nothing is sent anywhere.

You can also turn the search log on for some publisher websites (ScienceDirect, SpringerLink, MDPI, IEEE Xplore, Taylor & Francis Online, SAGE Journals, Wiley Online Library, Frontiers, ASCE Library, Nature.com, Science, Emerald Insight, ACS Publications, Cambridge Core, Oxford Academic, Canadian Science Publishing), one at a time, exactly as for the databases above: your browser asks for that site first, and LitRank then reads only that site's search results pages.

Website searches are kept apart from database searches in the log and in its totals, as the PRISMA reporting guidelines ask.

### 4. Save to LitRank (only when you ask)

When you right-click a page and choose **Save to LitRank**, or press the keyboard shortcut (Alt+Shift+L by default, which you can change), LitRank reads **that one page's citation details** (title, authors, journal, year, DOI, ISSN and PDF link, from the page's own metadata) and files the paper in your selected folder.

- It can read the page **only after you do this, only in that tab**, and only until you leave it. Your browser grants this one-tab access when you act.
- It reads the page's citation metadata only (on ScienceDirect, which publishes no author tags, also the article's own list of author names). It does not read the page's text, your sign-in, or any other tab.
- Nothing is sent anywhere by this. The paper goes into your local storage, and a small confirmation appears on the page.
- If the page is a PDF, LitRank saves that file to your Downloads folder instead (see **Save PDF** below), using only its address to tell which saved paper it belongs to.

### 5. Journal ranks on database results (on the sites you turned on)

On the results pages of Scopus, Web of Science, ScienceDirect and OpenAlex — only if you have turned that site on in the library, and only while **Show journal ranks** is on — LitRank reads the name of each result's journal as the page shows it and looks it up in the ranking data carried inside the extension, on your device. It then shows the journal's quartile, SJR score, country and open-access status beside it.

- Only the journal names shown on the page are read. Nothing about the results, the papers or you is stored, and nothing is sent anywhere.
- You can turn this off in the library at any time, and the badges disappear at once.

---

## What LitRank sends, and when

By default, **nothing** of yours. Three features make a network request, and each needs you to press a button first.

### 1. Fetch metadata

When you press **Fetch metadata** on a folder, LitRank asks [Crossref](https://www.crossref.org/) to complete the citation details of the papers in that folder: volume, issue, pages, and, for a paper that has a DOI, its authors and year.

- **What is sent:** the DOI, or the title, authors and venue, of the papers in *that folder only*
- **What is not sent:** your identity, your other folders, your search log, or anything about your browsing
- The request carries a fixed contact address that identifies **the extension**, as Crossref asks API users to do. It is not your email address, and it is the same for every LitRank user.
- Crossref handles the request under [its own privacy policy](https://www.crossref.org/operations-and-sustainability/privacy/)

### 2. Save PDF

When you press **Save PDF** on one paper, **Download PDF** on the confirmation after saving a page, or **Save to LitRank** on a PDF you have open, your browser downloads that one paper's PDF from the publisher that hosts it, using your own sign-in and library access. The publisher sees an ordinary download, exactly as if you had clicked the link yourself. Nothing is routed through us.

It saves **one file per press**. LitRank has no way to download many PDFs at once, on purpose: publishers can block a whole university's network for automated bulk downloading. If what arrives is not a PDF (a sign-in page, for example), LitRank deletes it rather than leave it on your disk under a .pdf name.

### 3. Load more results on Google Scholar, and Analyse this author

When you press **Load more** under Google Scholar's results, LitRank asks Google Scholar for the next page of the same search, as your browser would if you clicked "Next", and adds those results to the page you are on. The request goes to Google Scholar only, with your browser's own Scholar session, and nothing in it comes from LitRank.

**Analyse this author** on a profile does the same with Scholar's own **Show more** button, one page at a time with a pause between them, until the whole publication list has loaded.

---

## What LitRank never does

- ❌ No analytics, telemetry, crash reporting or usage statistics
- ❌ No advertising, and no advertising identifiers
- ❌ No selling, renting or sharing of data — there is no data held to sell
- ❌ No tracking across sites
- ❌ No reading of any page except: Google Scholar; the results pages of databases and publisher websites you turned on in the library; and the single page you ask it to save or to log
- ❌ No searching, clicking or downloading on your behalf on any site
- ❌ No bulk or automatic PDF downloading
- ❌ No use of your data to train anything

LitRank's use of any information is limited to providing and improving the features you can see. It is never transferred to a third party except as described above, and never used for advertising, creditworthiness, or lending purposes.

---

## Permissions, and why each one exists

| Permission | Why |
|---|---|
| Access to Google Scholar pages | To place badges and the filter bar on results, profiles and Labs pages, and to record Scholar searches if you turn that on. |
| `storage`, `unlimitedStorage` | To keep your saved papers, folders and search log on your device. A long reading list exceeds the small default quota. |
| `downloads` | To save the one PDF you ask for into `Downloads/LitRank/<folder>/`, check that what arrived is a PDF, and delete it if it is not. (Exports — BibTeX, CSV, JSON, the search log — are saved by the library page itself.) |
| `activeTab` | So that **Save to LitRank** and **Log this search** can read the one page you act on (or save the PDF you have open), in that tab only, only after you right-click or press the shortcut. It shows no warning at install. |
| `scripting` | To place the page reader and the confirmation on the page you act on, and, on the databases and websites you turn on, to attach the search-log reader and the journal-rank badges to their results pages. It can reach nothing you have not granted. It shows no warning at install. |
| `contextMenus` | The right-click items **Save to LitRank** and **Log this search**. It shows no warning at install. |
| `api.crossref.org` | Only for **Fetch metadata**, above. |
| Site access for a database, a publisher website or a library address (optional) | Asked for by your browser, one site at a time, when you turn the search log on for that database or website, or add a library address. Not granted at install. You can revoke any of it from the library or your browser's extension settings. |

At install time the extension asks only for the Scholar domains and the permissions above that are not marked optional. Access to any other site is asked for later, by your browser, one site at a time, and only if you turn on a database or add a library address.

---

## Folder sync

If you choose **Choose folder**, your browser shows you its own folder picker and you decide what LitRank may write to. The extension receives access to that one folder and nothing else, and writes the references, a CSV and a JSON file for each project there. Your browser can revoke that access at any time, and does so on its own schedule. Files are written by your browser directly to your disk — they do not pass through any server.

---

## Your data, your control

- **Export it:** BibTeX, CSV or JSON from any folder, and the search log as a Methods paragraph, a table, an appendix or CSV, at any time.
- **Delete some of it:** remove a paper, delete a search-log row, or delete a folder from the library.
- **Delete all of it:** "Delete every log row" clears the search log, and uninstalling the extension removes all of its storage. Nothing is retained anywhere else, because nothing was sent anywhere else.

There is no "request my data" process, because there is no copy of your data for us to hold. Requests under GDPR, CCPA or similar laws have nothing to retrieve — which is the point.

---

## Children

LitRank collects no personal information from anyone, of any age.

---

## Changes to this policy

If this policy ever changes, the revised version will be published here with a new effective date, and material changes will be noted in the extension's release notes. Continuing to use LitRank after a change means the new policy applies.

---

## Contact

Questions about this policy, or about anything the extension does:

**[Open an issue](https://github.com/riponcm/LitRank/issues/new)** · [github.com/riponcm/LitRank](https://github.com/riponcm/LitRank)

---

<sub>LitRank is an independent project and is not affiliated with, endorsed by, or sponsored by Google, Clarivate, Elsevier, ProQuest, EBSCO, Wiley, Springer Nature, Crossref, OurResearch (OpenAlex), the Allen Institute for AI, Scimago or the U.S. National Library of Medicine, or by any other database or publisher it works with. Google Scholar, Web of Science, Scopus, ScienceDirect, Embase, Engineering Village, ProQuest, EBSCOhost, Cochrane Library, PubMed and the other names mentioned are trademarks of their respective owners.</sub>
