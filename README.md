# jquery.formset
Django Formset using JQuery (fork from jQuery Formset 1.3-pre by Stanislaus Madueke)

This .js file has some corrections from the original version by Stan.
There was an error when you edit (or create) an InlineFormset with more than 2 rows.
This version mark the rows as deleted (hide them) and put the correct id's to their indexes.

*1.6-pre:*

Added ability for form's errors visualisation and each form's field errors by CSS classes.
Fixed error of deleted forms (TOTAL_FORMS submit equal only actual forms, but not deleted forms).
