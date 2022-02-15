Python script parses Confluence pages content through the REST API and makes csv with id, title, date, body, attachments and tags columns. You can use it to import as WordPress posts, for example. 

Usage:

Fill in the values of the `base_url`, `root_page_id`, `confluence_token` variables at the beginning of the file:
https://github.com/qzya/confluence-pages-to-csv/blob/05be428597c8b5a5d6b43e301e943a7dc65fa26e/confluence-pages-to-csv.py#L4-L6 
All this variables must be strings. See the comments in code.

Or uncomment next 3 lines, this will allow you to enter variable values during the execution of the script:
https://github.com/qzya/confluence-pages-to-csv/blob/05be428597c8b5a5d6b43e301e943a7dc65fa26e/confluence-pages-to-csv.py#L7-L9
