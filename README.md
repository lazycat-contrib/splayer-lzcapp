# SPlayer for LazyCat

SPlayer v3.0.0 (ghcr.io/imsyy/splayer) packaged as a LazyCat LPK (community store). Upstream v3.1.1 has no prebuilt image; latest available tag v3.0.0 used.

## Publication

MiaoMiao community store app 665, APPROVED, version 3.0.0. Built by reusable LazyCat workflow (run 41088022505) with mirror delivery verification. LPK 28160 bytes; SHA256 `bece490a714427125150d95bf317d90538fdaacb8d9ab1290ff109f171d1661f` downloaded independently and matched by the store at submission.

Single container (nginx frontend + netease API + unblock service in entrypoint), port 25884, no account system, no persistent volume declared. Duplicate check: official store has `iamxiaoe.lzcapp.splayer` (different package, kept as source), MiaoMiao full query for splayer returned 0 before submission.

No file-chooser interceptor, no smoke job. Configuration and synthetic checks only; device playback, source availability and lyrics not verified.
