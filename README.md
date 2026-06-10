# OpenArt License

The OpenArt License is a **trust‑network based licensing agreement** for artistic works. It is designed to resist policies, platform rules, or technical processing that may cause involuntary impairment of artworks, to protect the artist’s control over the integrity of their work, and to facilitate the free flow of unmodified artworks among artists.

## Highest Goal

**To build an artist‑maintained Trust Network in which unmodified artistic works can flow safely and completely, without relying on external legal systems or platform goodwill, while fully preserving the artist’s moral rights, including the right of attribution.**

Specifically:

- **Resist Impairment**: Any form of lossy compression, metadata removal, automatic watermarks, forced format conversion, etc., is considered an infringement upon the integrity of the work.
- **Technical Self‑Reliance**: Using encrypted archives, permissive platforms, member public‑key systems, and other technical measures, so that the distribution of artworks does not depend on any intermediary that might harm the work.
- **Trust over Rules**: Within the Trust Network defined by this License, the collective commitment of artists takes precedence over any conflicting law, policy, or platform term.
- **Individual Enforcement**: This License does not seek external judicial or administrative support. Its effectiveness comes solely from the voluntary compliance and mutual supervision of Trust Network members. Each artist is responsible for evaluating and enforcing the License personally.

## License Versions

Two independent versions of the OpenArt License are provided to suit different use cases:

| Version | Scope | Typical Use |
|---------|-------|--------------|
| **Original (Non‑Commercial Trust Network Edition)** | Non‑profit artistic works | Personal creative sharing, non‑commercial art exchanges, educational use, non‑profit exhibitions, etc. |
| **Commercial Edition** | Commercial artistic works | Works that may be sold, licensed, used in advertising, embedded in commercial products, used in for‑profit services, etc. (commercial authorization required separately) |

> The core provisions (work integrity protection, Trust Network mechanisms, technical distribution requirements, attribution, etc.) are identical in both versions. The only difference is whether commercial use is allowed. **The Original Edition strictly prohibits any commercial use**, while the Commercial Edition permits commercial use, possibly subject to additional licensing conditions.

## Purpose of the License

### 1. Establish a Trust Network

- Any artist who accepts this License and publishes a work automatically becomes a member of the Trust Network.
- Members mutually authorize each other – no separate agreement is required to exchange unmodified works.
- Trust is transitive: for works obtained from the Network, the scope of rights is always governed solely by this License.

### 2. Enforce Work Integrity Protection

- **Lossy compression is prohibited**: Even when used for archiving, lossy formats such as JPEG are presumed to cause impairment.
- **Metadata must not be altered**: EXIF, XMP, IPTC and other metadata must remain intact.
- **No automatic watermarks or markings**.
- **No platform may restrict download of original files or lock works into proprietary formats**.
- Members who violate these obligations will have their membership automatically suspended.

### 3. Technical Distribution Standards

- **Prefer “Permissive Platforms”**: Platforms that do not apply lossy compression, do not add watermarks, do not modify metadata, and do not restrict download of original files.
- **Encrypted Archive as fallback**: When a Permissive Platform is unavailable, the work must be distributed as an AES‑256 encrypted, losslessly compressed archive, with the password transmitted separately over a secure channel.
- A public preview version may use lower resolution or lossy compression, but must not replace the original work in member‑to‑member distribution.

### 4. Right of Attribution Remains Intact

- When using or distributing a work, you must clearly indicate the original author’s name (or pseudonym), the title of the work, and the name of this License, in a reasonable manner.
- For encrypted archives, the attribution information must be included in the password distribution information and be accessible before decryption.

### 5. Precedence over External Rules

- Within the Trust Network, the terms of this License have **supreme effect**.
- Any claim that “I am forced by law to violate this License” is not accepted under any circumstances – violators immediately lose all authorizations.
- Any responsibility arising from complying with this License while violating local laws, policies, or platform rules rests solely with the acting individual.

## How to Use This License

### For Artists (Publishers)

1. Include the following statement in the metadata, accompanying file, or distribution notice of the work you wish to protect:
- This work is licensed under the OpenArt License (Non‑Commercial Trust Network Edition).
- For details see [Link to full license text]
2. Provide both versions:
- **Unmodified Original** (original format, no lossy compression)
- **Public Preview Version** (may be lower resolution or lossy compressed, for preview)
3. Prefer to upload your work to a **Permissive Platform** (e.g., self‑hosted IPFS node, cloud storage that respects original files). If you must use a regular platform, create an encrypted archive and distribute the password via a secure channel.
4. You automatically become a member of the Trust Network. You are entitled to obtain works from other members under this License, but must comply with all its obligations.

### For Users (Recipients)

1. You obtain the right to use the work, provided that you also comply with this License (including no lossy processing, preserving attribution, non‑commercial use, etc.).
2. You may share the work with other Trust Network members, but you must not publish it on non‑permissive platforms or use it for commercial purposes.
3. If you violate any term of this License (e.g., uploading the work to a lossy‑compression platform), all your authorizations automatically terminate, and you must stop using and destroy any unmodified versions you have obtained.

## Technical Recommendations

- **Encrypted Archive**: Use 7‑Zip to create a `.7z` archive with AES‑256 encryption, compression level set to “Store” or “Fast” (lossless).
- **Permissive Platforms**: Self‑hosted IPFS distribution nodes, file hosts that preserve original downloads, direct member‑to‑member transfers, etc.
- **Member Authentication**: Trust Network members may voluntarily maintain a shared list of public keys for verifying encrypted password distribution.

## Limitations and Disclaimer

- **This License grants no commercial use rights (Original Edition).** For commercial use, please contact the author to obtain a Commercial Edition license.
- Works are provided “AS IS”. The author assumes no direct or indirect liability arising from the use of the work.
- This License does not seek recognition or enforcement by any external legal system. Its validity is derived solely from the voluntary compliance and mutual supervision of its members.

## Full License Texts

- **Original Edition (Non‑Commercial Trust Network Edition)**: [OpenArt_License_NonCommercial_EN.md](OpenArt_License_NonCommercial_EN.md)
- **Commercial Edition**: Please contact [email/website] to obtain the Commercial Edition license text.

## Join the Trust Network

Any artist who publishes a work under this License automatically becomes a member of the Trust Network. You are invited to participate by:

- Tagging your work with `#OpenArtTrustNetwork`
- Joining community discussions ([Matrix/Discord/forum link])
- Sharing your experience with Permissive Platforms or encrypted distribution toolchains

---

**OpenArt License – Let art remain whole, and let trust replace coercion.**