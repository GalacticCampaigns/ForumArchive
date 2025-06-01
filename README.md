# Galactic Campaigns - Forum Archive

Welcome to the official archive of the **Galactic Campaigns** play-by-post roleplaying game forum! This repository preserves the stories, characters, and discussions from our community, which primarily focused on Star Wars RPGs.

The content here has been exported from the original phpBB SQL database and converted into Markdown (`.md`) format for readability and preservation.

## About Galactic Campaigns

Galactic Campaigns was a vibrant community dedicated to play-by-post roleplaying games, with a strong emphasis on the Star Wars universe. This archive contains the sagas, adventures, and out-of-character discussions that made our forum a special place. The majority of the threads converted are from these collaborative storytelling games.

## Navigating the Archive

The content is organized to mirror the original forum structure:

* **Root Directory**:
    * `forum_and_thread_index.csv`: A master list of all forums and threads, including their original IDs and titles. This is a good place to start if you're looking for something specific.
    * `script_execution_log.txt` (Optional): Contains logs from the export script execution.
* **Category Folders**: The main subdirectories (e.g., `Star Wars Games`, `General Discussion`) represent the top-level categories from the original forum.
* **Forum Folders**: Within each category, you'll find folders representing individual forums. For game categories, these often correspond to specific campaigns or game systems.
* **Thread Files (`.md`)**: Inside each forum folder, individual Markdown files (`.md`) represent the threads. Filenames are typically in the format `Thread_Title_topicID.md`.

**Example Path:** `Star_Wars_Saga_Edition_Games/The_Coruscant_Caper/Episode_1_The_Heist_topic123.md`

## Content Format

All forum posts have been converted to Markdown. This includes:
* Basic text formatting (bold, italics).
* Quotes.
* Code blocks.
* Lists.
* Links and images (where possible, pointing to original URLs if they were external).

Custom BBCodes from the original forum have also been converted based on their definitions in the database.

## Source and Conversion

* **Source**: Data was extracted from a SQL backup of the phpBB forum database.
* **Conversion**: A custom Python script (`phpbb_to_md_exporter_v3`) was used to query the database, parse BBCode (including custom codes), and generate the Markdown files and directory structure.

## Notes

* While every effort has been made to ensure accurate conversion, some complex BBCode or embedded content might not render perfectly.
* External links or image URLs within the posts are preserved as they were in the original database; their continued availability is not guaranteed.

Thank you for visiting the Galactic Campaigns archive! We hope you enjoy revisiting these adventures.