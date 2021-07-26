To add a featured image to a publication simply add a featured.png or featured.jpg file into the respective folder.

To add a post execute

hugo new --kind post post/post-name

To add a new project

hugo new --kind project project/project-name

To add software

hugo new --kind software software/mysoftware-name

Bibliography:
-------------

To add the biliography simply add your entry in the corresponding bib file. Ideally as obtained from DBLP (if available -- will not be the case for the newest ones).

To associate a PDF upload it to the Google drive for the respective year. This should be in the uncbiag-public-pdfs folder on Google drive. Make sure you give it a readonable name of the form: myname_2020_great_paper.pdf. Then follow the following steps:

1, Click on it in the google drive to open it.
2. Click on the three dots in the top right and select 'Open in new window'.
3. For the document in the new window again click the three dots in the top right and select 'embed document'.
4. From the 'embed document' popup copy the URL (everything *excluding* /preview) and add it as the url entry in bibtex. I.e., url = {https://drive.google.com/ssdfsdfsdfsdfds},

Now you can compile the bibliography by executing

academic import --bibtex uncbiag-bibliography.bib

For this you will need to have this package installed. See
https://github.com/sourcethemes/academic-admin

If you want to overwrite entries (CAREFUL WITH THIS) then run

academic import --overwrite --bibtex uncbiag-bibliography.bib

Now you should be able to see your publication. For example, by running:

hugo server

from the main directory.

If the PDF link worked you should see the PDF rendered at the bottom of the bibliography entry.

