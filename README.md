Plain text EUPL v1.1
====================

Plain text UTF-8 conversion of EUPL v1.1 license.

Original PDFs are available on [the EUPL page](https://joinup.ec.europa.eu/software/page/eupl/licence-eupl).

PDFs are converted with [pdftotext](http://www.foolabs.com/xpdf/download.html),
and then reformatted with vim using `gq` and `:center 80`.

 * Use these files without any moderation.
 * Pull requests are welcomed.


Style
-----

The style is the following one:

 * Two blank lines after the title and the author of the license.
 * Two blank lines before a section title.
 * Four spaces before a section title.
 * One blank line between two paragraphs.
 * One space before a bullet point.
 * Three space before a new line in a bullet point (in order to be aligned with the text of the first line of the bullet point).
 * Blank line before and after lists.
 * No blank line between bullet points, except for the "definitions" and "obligations of the licensee".
 * Depending on the languages lists are `*` for bullet points, and `-` (hyphen) for em-dashes.
 * The copyright sign is converted to `(c)`.
 * Typographic apostrophes are converted to simple `'`.
 * Typographic quotes are converted to simple `"`.
 * Appendix becomes a normal section without any number. (`====` is removed)

Footnote about "EUPL" is added to the definition list.


Why should I use the EUPLv1.1?
------------------------------

The EUPL has been designed for European Union member country. It is just a
European version of the GPLv2 and can be converted to GPLv2 or CeCILL-C.

It has been approved by the OSI and the FSF.

There are multiple reason to use the EUPLv1.1:

 * You are a company based in the European Union, and you want full European
   copyright protection for your software.
 * You want to show your pride of being an European Citizen.
 * You want to distribute an open source software in Europe.
 * You want a legal license in your local language (which is not English).
 * You want to be protected by the lack of software patent in the European Union.
 * You want a copyleft license
   [approved by the FSF](https://www.gnu.org/licenses/license-list.html#EUPL)
   and [the OSI](http://opensource.org/licenses/EUPL-1.1).

Why shouldn't I use the EUPLv1.1?
---------------------------------

 * You don't want copyleft, and you want a permissive license.
 * You want tivoization protection.
 * You want an
   [GNU AGPL](https://en.wikipedia.org/wiki/Affero_General_Public_License)-like
   license.
 * Your company is not based in the European Union.
 * You want to write closed-source software.


I don't want my software to be ruled by belgian law!
----------------------------------------------------

The section 15 specifies that the Belgian law overrules any European law, in
case there would be a conflict between local laws.

To be clear, European Countries laws are very uniform few conflict might arise.
Moreover, Belgium has to enact European directives. Therefore, this is would be
a legal edge case. Don't worry about that.


Why isn't there my language?
----------------------------

This is a manual process. I reformatted them, and eyeballed them to make sure
it was right.

So of course I only did languages in which I have notions. If you want to add
your language, please do so by emailing me or opening a pull request.
