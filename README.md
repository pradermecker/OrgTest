# OrgTest

Alternatives will depend on the general `latex class` configuration:

    ;; paragraph
    (add-to-list 'org-latex-classes
                 '("pi3r-org-article"
                   "\\documentclass{scrartcl}
                   "
                   ("\\section{%s}" . "\\section*{%s}")
                   ("\\paragraph{%s}" . "\\paragraph*{%s}")

    ;; subsection
    (add-to-list 'org-latex-classes
                 '("pi3r-org-article"
                   "\\documentclass{scrartcl}
                   "
                   ("\\section{%s}" . "\\section*{%s}")
                   ("\\subsection{%s}" . "\\subsection*{%s}")

    ;; itemize/enumitem
    (add-to-list 'org-latex-classes
                 '("pi3r-org-article"
                   "\\documentclass{scrartcl}
                   "
                   ("\\section{%s}" . "\\section*{%s}")


Then you can switch from `itemize` to `enumitem` chosing N=1 or N=2
