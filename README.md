# webstorm-ts-declare-issue-reproducer

1. Run against node >= 10; yarn or npm doesn't matter
2. install dependencies
3. Open in Webstorm 2020.2
4. Open the file "src/bla/OfferFilter.ts.vue"
5. Notice that the TS Language Checker emits `Error:(9, 19) TS2304: Cannot find name 'MyOffer'.`, even tough it's declared in src/interfaces/blubb/MyOffer.d.ts and command-clicking is possible.

