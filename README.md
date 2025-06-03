Galactic Campaigns - Forum Archive
==================================

Welcome to the official archive of the Galactic Campaigns play-by-post roleplaying game forum! This repository preserves the stories, characters, and discussions from our community, which primarily focused on Star Wars RPGs.

The content here has been exported from the original phpBB SQL database and converted into Markdown (`.md`) format for readability and preservation. While the bulk of the forum has been processed and formatted, ongoing improvements are always welcome, particularly for smilie rendering and ensuring clean list structures within complex posts.

About Galactic Campaigns
------------------------

Galactic Campaigns was a vibrant community dedicated to play-by-post roleplaying games, with a strong emphasis on the Star Wars universe. This archive contains the sagas, adventures, and out-of-character discussions that made our forum a special place. The majority of the threads converted are from these collaborative storytelling games.

Navigating the Archive
----------------------

The content is organized to mirror the original forum structure:

*   Root Directory:
    
    *   `forum_and_thread_index.csv`: A master list of all forums and threads, including their original IDs and titles. This is a good place to start if you're looking for something specific.
        
*   Category Folders: The main subdirectories (e.g., `Star Wars Games`, `General Discussion`) represent the top-level categories from the original forum.
    
*   Forum Folders: Within each category, you'll find folders representing individual forums. For game categories, these often correspond to specific campaigns or game systems.
    
*   Thread Files (`.md`): Inside each forum folder, individual Markdown files (`.md`) represent the threads. Filenames are typically in the format `Thread_Title_topicID.md`. Each file also includes a "Last Modified" timestamp at the bottom indicating when it was last processed by the export script.
    

Example Path: `Play_by_Post_Roleplaying_Games/Star_Wars_Play-by-Post_Games/Star_Wars_Forgotten_Ones/Regulations_25419.md`

Content Format
--------------

All forum posts have been converted to Markdown. This includes:

*   Basic text formatting (bold, italics).
    
*   Quotes.
    
*   Code blocks.
    
*   Lists (including nested lists - though complex cases inside spoilers are an area for ongoing refinement).
    
*   Links and images (where possible, pointing to original URLs if they were external, or using new URLs for smilies if provided in the database).
    
*   Spoilers (rendered using HTML `
` tags for collapsibility, with content correctly formatted as Markdown).
    

Custom BBCodes from the original forum have also been converted based on their definitions in the database or handled by specific logic in the export script.

Source and Conversion
---------------------

*   Source: Data was extracted from a SQL backup of the phpBB forum database.
    
*   Conversion: A custom Python script (latest version: `phpbb_to_md_exporter_v4.0.28` or newer) was used to query the database, parse BBCode (including custom codes), and generate the Markdown files and directory structure.
    

How to Contribute & Assist
--------------------------

The conversion process, while largely successful, may not have perfectly formatted every single post, especially those with highly complex or unusual BBCode (e.g., smilies with surrounding HTML comments, deeply nested lists within spoilers). Your help in identifying and correcting these instances is greatly appreciated!

There are two main ways you can assist:

### 1\. Reporting Formatting Issues

If you come across a page or post that is poorly formatted, please help us by reporting it. The best way to do this is by:

*   Creating an Issue: On the GitHub repository page for this archive, please open a new "Issue".
    
*   Providing Details: In your report, please include:
    
    *   The full path to the Markdown file (e.g., `Play_by_Post_Roleplaying_Games/Star_Wars_Play-by-Post_Games/Star_Wars_Forgotten_Ones/Reflections_[OOC]_25420.md`).
        
    *   The Post ID (if visible or known) or a clear description of which post within the file has the issue (e.g., "Post by BWS2K on 2014-04-11 21:24:11").
        
    *   A description of the formatting problem (e.g., "smilie comments still visible around image," "list not rendering correctly inside spoiler," "unconverted BBCode tag `[foobar]`").
        
    *   If possible, a snippet of the original BBCode from the `post_text` (if you have access to the database or an older version of the file) can be very helpful.
        

### 2\. Making Updates (for Approval)

If you are comfortable with Markdown and Git, you can also directly contribute fixes:

1.  Fork the Repository: Create your own copy of this archive on GitHub.
    
2.  Create a Branch: Make a new branch in your fork for your changes (e.g., `fix/formatting-issue-topic123`).
    
3.  Edit the File(s): Make the necessary corrections to the Markdown in the affected file(s).
    
4.  Commit Your Changes: Save your changes with a clear commit message (e.g., "Fix: Corrected list formatting in Reflections OOC post X").
    
5.  Submit a Pull Request: Open a pull request from your branch to the main archive repository. Please describe the issue you've fixed in the pull request.
    

Your contributions will be reviewed and merged if they improve the archive's quality.

Notes
-----

*   While every effort has been made to ensure accurate conversion, some complex BBCode or embedded content might not render perfectly. Ongoing efforts aim to address these.
    
*   External links or image URLs within the posts are preserved as they were in the original database (or updated for smilies where new URLs were provided); their continued availability is not guaranteed.
    

Thank you for visiting the Galactic Campaigns archive, and thank you for any assistance you can provide in making it even better!
