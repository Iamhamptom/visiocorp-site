# visiocorp.co — published site

Built output only. Source lives in the private repo `Iamhamptom/VisioCorp`
(`~/Documents/VisioCorp (web Suite)` on the Mac).

Rebuild and republish:

    cd ~/Documents/"VisioCorp (web Suite)" && npm run build
    python3 ~/hampton-music/client-engine/make_legal_site.py   # /terms/ + /refund-policy/
    # then copy dist/ into this repo and push

`/terms/` and `/refund-policy/` are generated from the same source as the PDF
documents sent to Payfast — never edit them here by hand, they will be overwritten.
