# Nearcress 1.0 TEST
Native Android Myopia. These small boards are original generated layouts. Android 8+ (min 26), target 35. Package com.gg007.nearcress.

## Rules
Myopia. Draw one closed, noncrossing, unbranched loop on the dotted grid edges. Each clue contains ALL directions (up, right, down, left) in which a loop edge is nearest when looking orthogonally from that cell center. Compare the first visible perpendicular edge in each of the four directions; missing directions are farther than any visible edge. Equal closest distances require every tied direction, and no others. Blank cells impose no restriction. Clues do not have to lie inside the loop. Twelve original unique 3x3-cell arrow boards and twelve distinct loops. Tap gaps between dots to toggle roads. Undo/reset/next/levels and saved loop palette/direction letters.

## Download and status
https://mega.co.nz/#!wcMjCDqA!WgeVaLLVrmzxNioRdBKCBOuPJBR-sZMfPbuVPqIN8ds
APK SHA256 b5b9d6be1d3c8f0c5efdb392af626515981577a2c9aeca33f654d88bc2b3b0e8; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Original portable generator enumerates all 213 simple cycles on a 4x4-dot grid and creates twelve uniquely constrained 3x3-cell arrow boards. Independent Java ordered-cycle tracing agrees with production degree/BFS topology on ALL 16,777,216 edge masks. Independent doubled-coordinate ray intersections agree with production grid-index nearest-edge distances on all 213 loops for all twelve boards; each has exactly one solution. Another 120,000 random/invalid arrow-mask cases include 1,080,000 nearest-direction comparisons; 288 single-edge mutations, bounds, solved lock and solve/undo/replay/reset pass. Archived generator reproduces levels.json and all-cycles.json byte-for-byte; archived Java passes. Drawing adapter tests actual road taps, undo/replay/next/levels/menu/settings/privacy and saved palette/direction letters/completion. Six drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry and semantic review of all 165 prior studio cards found no base Myopia match. Towercress counts parallel road edges and requires tower inside/outside; Brindlepath counts dark cells along arrows; Exitcress fixes room-departure run lengths. Nearcress instead compares distances to the nearest perpendicular loop edge in all four directions, including complete ties. Known Myopia genre, not a global invention. Primary rules https://www.gmpuzzles.com/blog/2021/04/myopia-by-ashish-kumar/ and https://ericfox53.blogspot.com/2021/04/245-myopia.html define the selected behavior. Yajilin Myopia and black-cell shading variants were not selected. No source puzzle copied; original generated arrow layouts. Recovered repository corpus remains partial.

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated arrow-direction clues and road solutions. javac -d /tmp/near-test src/com/gg007/nearcress/Board.java BoardTest.java and java -cp /tmp/near-test com.gg007.nearcress.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Nearcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Loop palette, direction letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/wtnddckd63l0-nearcress-source-archive, including exact cumulative 166-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/nearcress holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
