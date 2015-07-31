Aurora with and without Devtools
================================

This is revision e24d6e451e85 of mozilla-aurora.

I made the following edits:

    rm -rf browser/locales/en-US/chrome/browser/devtools
    rm -rf toolkit/locales/en-US/chrome/global/devtools
    rm -rf dom/locales/en-US/chrome/layout
    rm -rf dom/locales/en-US/chrome/[sx]*
    rm -rf security/manager/locales/en-US/

See the result on http://pike.github.io/no-devtools/.
