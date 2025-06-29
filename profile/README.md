# 📌 SLC MILESTONE DEVELOPMENT PLAN

**Development Target: November 2025 (5 Months)**

---

## MONTH 0 — JUNE: FOUNDATION SETUP _(Completed)_

**Deadline: June 30, 2025**  
✅ Tasks:
- Server setup — Backend (Coolify)
- OHIF Viewer initial configuration
- Orthanc server for PACS & DICOM service
- Backend foundation setup (models, database)

---

## MONTH 1 — JULY: CORE WORKFLOW DEVELOPMENT

**Timeline:** July 1 – July 31, 2025  
**Assessment:** August 1 – August 7, 2025  

✅ Tasks:
- Role-based user authentication flow & 2FA system
- PACS + manual DICOM upload support
- Metadata extraction & storage (StudyInstanceUID, SeriesInstanceUID, etc.)
- Searchable worklist (by patient ID, modality, date)
- Admin dashboard for study assignment & tracking

### OHIF Viewer Development – Phase 1
- Viewer embedding & route-based study loading (`/viewer?studyUID=...`)
- Basic viewer UI integration (toolbar, overlays, viewport layout)
- Custom toolbar cleanup (remove unused tools)
- Measurement tools review & activation
- UI header customization (Patient ID, Modality, Study Date)
- Viewer-user context bridge (logged-in user awareness)

🎯 **Goal:**  
End-to-end flow: Upload → Worklist → View in OHIF (clean UI, basic measurements)

---

## MONTH 2 — AUGUST: REPORTING SYSTEM

**Timeline:** August 8 – August 31, 2025  
**Assessment:** September 1 – September 7, 2025  

✅ Tasks:
- Specialist structured report editor (Radture Report Console)
- Report status flow: Draft → Assigned → Approved
- Templates per modality (e.g., chest X-ray, CT brain)
- Delta reporting with side-by-side comparison (manual select)
- Admin approval system with edit history & logs
- PDF export, internal delivery to referring doctor

### OHIF Viewer Development – Phase 2
- Add "Write Report" button to OHIF (opens editor or side panel)
- Screenshot capture tool (attach image to report)
- Annotation save/export mechanism (backend or report context)
- Manual comparison view (load prior/current series side-by-side)

🎯 **Goal:**  
Link viewer with reporting system for a full reporting loop

---

## MONTH 3 — SEPTEMBER: PATIENT DELIVERY & FOLLOW-UP

**Timeline:** September 8 – September 30, 2025  
**Assessment:** October 1 – October 7, 2025  

✅ Tasks:
- Secure report delivery via tokenized links (RadtureLink Lite)
- Email/SMS delivery infrastructure
- Report privacy controls (one-time view, expiry, device lock)
- Follow-up scheduling UI (admin only)
- Report download & print support (PDF)

🎯 **Goal:**  
Patient + doctor report access, secure and trackable

---

## MONTH 4 — OCTOBER: ANALYTICS, QA TESTING, PILOT READINESS

**Timeline:** October 7 – October 31, 2025  
**Assessment:** November 1 – November 7, 2025  

✅ Tasks:
- Usage analytics dashboard (case volume, turnaround times)
- Penetration/security testing (platform + PACS endpoints)
- Viewer access/activity logging (who opened what, when)
- Error handling UI in OHIF (study not found, load failed)
- UX polish (loading speed, measurement UX, layout)
- Final documentation for hospital onboarding

### OHIF Viewer Development – Phase 3
- Add clean error/loading states in viewer
- Auto-save draft state of annotations before report completion
- Optional: light PHI overlay suppression (clean screenshot export)

🎯 **Goal:**  
Polished, monitored, and auditable system for real-world testing

---

## MONTH 5 — NOVEMBER: SLC LAUNCH

✅ Tasks:
- Pilot onboarding (2–3 hospitals, 3–5 radiologists)
- Collect structured feedback from users
- Live usage data collection (time to report, case volume)
- Prepare investor demo system (end-to-end flow)

🎯 **Goal:**  
Live, end-to-end clinical pilot with credible metrics and demos


---

## 🧭 DISCIPLINE NOTE:

- ❌ **No Scope Creep** — Only core SLC features will be discussed
- ✅ **Weekly Sprint Reviews** — Saturday & Sunday
- ✅ **Monthly Milestone Assessments** + Feature Integration
- ❌ **AI, advanced follow-up, automation** deferred post-SLC

---

## 🔒 LOCK-IN WATCH WORD:

> **STAY LEAN AND DISCIPLINED!**

