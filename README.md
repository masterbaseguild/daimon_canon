# Daimon Canon

## What is this repository?
Daimon Canon is the official repository containing the entire narrative canon of the Daimon project, located at [https://daimon.world](https://daimon.world).

Anything found within the original copy of this repository (`masterbaseguild/daimon_canon`) is considered fully canonical at the time of reading, though it may be subject to modifications in the future.

## How does it work?
Any author who wishes to contribute to the repository can fork it and propose a Pull Request (PR). The Daimon Team will review the PR, contact the authors to discuss any necessary adjustments (ensuring the new additions remain strictly consistent with the current canon) and ultimately approve the PR if it meets the criteria.

The goal is to build an open-source narrative universe where anyone can add content. Submissions are carefully selected, reviewed by a team of supervisors, and officially canonized once they fulfill the requirements.

## Licensing & Community Rules
By participating in this project, you agree to uphold our community standards and licensing framework:

*   **Licensing:** This entire project is an open-source universe. All text, lore, and contributions are licensed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license. You can read the full legal text in our [LICENSE.md](./LICENSE.md) file.
*   **Code of Conduct:** We are committed to fostering a welcoming, creative, and respectful environment. All contributors must adhere to our Code of Conduct, based on the Contributor Covenant, which can be found in [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

## Developer Certificate of Origin (DCO) & Pseudonym Policy
To protect the integrity of the universe and ensure all content can remain open-source forever, we use a Developer Certificate of Origin (DCO) process. 

### How to Sign Off Your Work
Every commit you submit via a Pull Request must be signed off. You can do this automatically by adding the `-s` flag to your git command:
`git commit -s -m "Example commit name"`

This appends a `Signed-off-by: Name <email>` line to your commit, certifying that you are the original creator of the text and have the right to license it under CC BY-SA 4.0.

### Pseudonym Policy
We understand that many writers prefer to publish under pen names. **Pseudonyms are allowed and highly encouraged.** However, please note that if you choose to sign off using a pseudonym, it is the author's sole responsibility to prove ownership of that pseudonym/handle should any legal or copyright ownership issues arise in the future.

## I want to keep certain aspects of my fork secret to reveal them later. How can I do that?
In this case, we recommend cloning your fork and making that cloned repository private. You can then work directly on that private copy and push to your public fork only the material that is ready to be revealed to the public. 

However, we strongly advise contacting the review team first and granting them read access to your private copy. This helps avoid unpleasant surprises at the last minute (for example, finding out a major plot reveal contradicts the established canon).

## How will the canon repository sync with live material?
The repository `live` branch stores the current canonical version of the narrative universe. The Daimon Frontend pulls directly from said branch via the GitHub API. We are planning a system of pipelines, harnessing GitHub Actions, to handle large files (such as audio tracks or images), by uploading them to the Daimon Media Directory. If you wish to include external files in your content, reach out via Pull Request or on Discord at [https://masterbase.team/links/discord](https://masterbase.team/links/discord) for further information.

## Other ideas currently in the experimental phase
*   **Unreliable Narration:** An interesting concept that could greatly facilitate our work is framing parts of the material as coming from biased or sometimes even conflicting sources.
*   **Anti-Spoiler Filters:** A more technical idea involves implementing anti-spoiler filters within Daimon to protect unsuspecting users from major narrative reveals ahead of their current progress in specific storylines.

For the time being, these remain strictly conceptual.

---

# Rules

1.  **Filenames & Content:** All filenames must be in English, and the content of each file must be written in its corresponding language directory (`/en` or `/it`).
2.  **Character File Placement:** Every character's file must be placed in the folder of the last faction they belonged to in their lifetime (defined as their primary faction).
3.  **Cross-Referencing:** The first mention of any file/entity within a text must be hyperlinked to its respective file.
4.  **Translations & Proper Nouns:** For translations, unless a native real-world equivalent already exists (e.g., *Earth* in English / *Terra* in Italian), all proper nouns must be kept in their original, primary form.