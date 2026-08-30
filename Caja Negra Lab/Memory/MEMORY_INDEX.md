CAJA NEGRA LAB — MEMORY INDEX  
VERSION: 2.0  
\[PROJECT:CN-LAB\] \[TYPE:MEMORY\] \[SYSTEM:GLOBAL\] \[STATUS:VERIFIED\]  
PURPOSE: Fast routing. Read this before loading large memories.

ROOT\_FOLDER\_ID: 1w1\_m5sLst6SD26mzFpHk4GnsO\_GpfSo-  
MEMORY\_FOLDER\_ID: 1\_7kukRM0LbGTu2g4eXmnBs7iNrSIvPiW  
ARCHIVE\_FOLDER\_ID: 1pJYJoX7xFsfy3pjy07eiweDHDkzpsU9N

CURRENT MEMORY PROTOCOL  
ID: CN-MEM-PROTOCOL-V3  
FILE: MEMORY\_PROTOCOL\_V3 — Cerebro Operativo V23  
DOCUMENT\_ID: 1Wmluc\_CVJVytBcjoTZwzH3g25PRqchyZahnWeMrlLZo  
STATUS: APPROVED / CURRENT  
SUPERSEDES: MEMORY\_PROTOCOL\_V2 operationally.

FAST START  
1\. Read MEMORIA MAESTRA.  
2\. Read MEMORY\_INDEX.  
3\. Recover newest checkpoint from EXECUTION\_HISTORY.txt.  
4\. Establish MISSION / FRONTIER / CHECKPOINT for the current task.  
5\. Load only targeted current-state knowledge/procedure/evidence needed.  
6\. Verify actual Drive state before acting.  
7\. Follow MEMORY\_PROTOCOL\_V3 for resolve/guard/verify/persist/handoff.

IDENTIFICATION SCHEME  
\[PROJECT:CN-LAB\]  
\[TYPE:MEMORY|EXEC|DECISION|ISSUE|SYSTEM|CHECKPOINT|ARCHIVE\]  
\[SYSTEM:GLOBAL|ECONOMY|MARKET|PRODUCTION|CONTRACTS|WAREHOUSE|FUSION|BOTS|TELEMETRY|RETENTION|UI|SECURITY|OTHER\]  
\[STATUS:PROPOSED|APPROVED|IMPLEMENTED|VERIFIED|FAILED|PENDING|SUPERSEDED|NEEDS\_REVIEW\]  
\[ID:\<stable-id\>\]  
\[DATE:YYYY-MM-DD\]  
\[TAGS:comma,separated,keywords\]  
\[LINKS:\<related IDs\>\]

CHAIN RULE  
Every significant execution closes with PREV / THIS / NEXT / STATE\_HASH.  
THIS becomes PREV for the next checkpoint. Broken chains are reported and recovered, never silently repaired.

CURRENT INDEX  
CN-MEM-ROOT | MEMORY | GLOBAL | VERIFIED | 2026-08-29 | Caja Negra Lab — MEMORIA MAESTRA | Drive root/Caja Negra Lab | recovery,protocol,source-of-truth | Entry router and canonical recovery instructions.  
CN-MEM-INDEX | MEMORY | GLOBAL | VERIFIED | 2026-08-29 | MEMORY\_INDEX | Memory/ | index,tags,routing | Fast map for memories, protocol and archives.  
CN-MEM-PROTOCOL-V3 | MEMORY | GLOBAL | APPROVED | 2026-08-29 | MEMORY\_PROTOCOL\_V3 — Cerebro Operativo V23 | Memory/ | brain,protocol,mission,frontier,checkpoint,trust,dependency,compression | Current operational memory protocol. Supersedes V2.  
CN-EXEC-ACTIVE | EXEC | GLOBAL | VERIFIED | 2026-08-29 | EXECUTION\_HISTORY.txt | Drive root/Caja Negra Lab | execution,history,forensic,checkpoint | Active append-only operational chain.  
CN-BIBLE-ECO-V2 | SYSTEM | ECONOMY | VERIFIED | 2026-08-29 | Caja Negra Lab — Economía v2 | Drive root/Caja Negra Lab | economy,bible,current-design | Canonical current economic design.  
CN-BITACORA | DECISION | GLOBAL | VERIFIED | 2026-08-29 | Caja Negra Lab — Bitácora maestra | Drive root/Caja Negra Lab | decisions,history | High-level summarized evolution.

SEARCH / RECOVERY STRATEGY  
Do not read everything by default.  
1\. Anchor current GOAL and FRONTIER.  
2\. Use this index to locate SYSTEM/TAG/ID.  
3\. Read latest checkpoint.  
4\. Read targeted specialized/current-state memory if listed.  
5\. Read relevant evidence/history only when necessary.  
6\. Expand scope only if MEMORY\_GAP remains.  
Goal: most known context should resolve ROUTER \-\> INDEX \-\> ONE TARGET FILE.  
If a class of task repeatedly requires broad searches or \>3 unrelated files, improve routing/indexing or create a justified SYSTEM\_\<NAME\> memory.

SPECIALIZED MEMORY RULE  
Create Memory/SYSTEM\_\<NAME\> only when it materially reduces complexity or retrieval cost, including when: 5+ significant decisions exist for that system; the same context is re-read in 3+ executions; parameters/interfaces are easy to confuse; history becomes too large; or retrieval difficulty caused a failure.  
Do not duplicate the Bible. Product conclusions inside specialized memory remain PROPOSED until approved/promoted.

AUTO-ARCHIVE RULE  
Archive oldest complete closed blocks when active EXECUTION\_HISTORY reaches any threshold:  
\- 1,500 lines OR  
\- 250 KB OR  
\- 100 execution entries OR  
\- 60 calendar days.  
Before archive, create a compact MILESTONE with IDs, decisions, failures, lessons and unresolved items. Preserve pointers. Never delete evidence/history needed for reconstruction.

PERSISTENCE / LEARNING RULE  
New information must resolve to DROP / APPEND / UPDATE / SUPERSEDE / PROMOTE.  
Learning progression: OBSERVATION \-\> HYPOTHESIS \-\> EVIDENCE \-\> CANDIDATE \-\> CANONICAL.  
Do not promote by repetition. Preserve authority/provenance. If a premise changes, mark affected dependents NEEDS\_REVIEW and reevaluate only that affected set.

COMPRESSION RULE  
Current state should stay compact. History may grow.  
Compress duplicates/closed episodes only when SUMMARY \-\> SOURCE remains recoverable and meaning, authority and state are preserved.

CLOSURE RULE  
A task closes only when DONE\_WHEN is evidenced and no required ACTIVE/PENDING/BLOCKED or relevant NEEDS\_REVIEW remains. Otherwise record PARTIAL/BLOCKED and hand off exact next action.  
