# AgentGate: supplementary archive

Archive for the paper **AgentGate: A Verifiable Gateway for Classifying and Auditing
Autonomous Agent Actions** (Hamdan Almessabi, Saif Alazazi, Abdulrahman Alnaqbi,
Khaled Alsaadi, Artur Koci; Abu Dhabi Polytechnic).

| File | What it is |
|---|---|
| `AgentGate_AIR2026_artifact.zip` | Archive **version 4** (build 3 of the six programs): source closure, specifications, oracle, raw data and scripts, sample evidence bundles, the partial Python verifier, test vectors, and the documents S1–S17 the paper refers to as "archive Sx". 32 MB, 3,849 files. |
| `AgentGate_AIR2026_artifact.zip.sha256` | Its SHA-256 in `sha256sum -c` format. |

SHA-256 of the archive:

```
edd69860e236b90460be28546afc0dab67982010988b04b6149ae9fe6fdf582b
```

The paper prints the first 16 hex digits of this digest in its Artifact Availability
section. The archive's own `README.md` gives the environment (Go 1.26.6 offline, Python 3) and
the commands that rebuild the six programs reproducibly and recompute the paper's tables
(`regenerate_tables.py`); `BINARIES_SHA256.txt` lists the binary hashes a rebuild must give.

The archive is provided for review of the paper; see `PROVENANCE.md` inside it for the
licence position. It contains no private key and no personal data.
