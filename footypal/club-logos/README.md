# Club logos

One PNG per club, named by the club's team id from `data/seed-afl2026/teams.csv`
(ADEL, BRIS, CARL, COLL, ESS, FRE, GCS, GEEL, GWS, HAW, MELB, NMFC, PORT, RICH, STK, SYD, WB, WCE).

Every club badge on the site comes from this folder through `src/components/TeamLogo.tsx`,
so replacing a file here (same name) updates that club everywhere. Keep them square with a
transparent background; 256x256 is plenty for the largest size shown (64px).

These are original designs based on club colours, not the official AFL logos.
