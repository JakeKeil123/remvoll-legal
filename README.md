# Remvoll legal documents

The published copies of Remvoll's Privacy Policy, Terms of Service and related
documents, served by GitHub Pages so App Store Connect has a working
**Privacy Policy URL** and **Support URL**. Apple requires the privacy policy to
be linked from App Store Connect metadata *and* reachable in the app
(App Review Guideline 5.1.1(i)), which is why both copies exist.

**Everything here is GENERATED.** The source of truth is
`ios/Remvoll/Legal/Legal.swift` in the (private) Remvoll app repository, which is
the same text the app renders offline. Do not edit these files by hand: they are
overwritten. Edit the Swift and run:

    python3 ios/Tools/gen-legal-web.py --site <path-to-this-checkout>

This repository is public **only** so GitHub Pages can serve it. It contains no
application source.
