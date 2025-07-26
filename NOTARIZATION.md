# AIGO Project - Notarization Record

This document serves as the official notarization record for the **Artificially Intelligent Geoecological Organization (AIGO)** whitepaper and associated materials.

All files and their integrity proofs are permanently verifiable via **IPFS** and **anchored to the Bitcoin blockchain** using OpenTimestamps.

---

## Primary Ledger

The master notarization ledger for this project is:

- **File:** `final_proof.json`
- **IPFS CID:** (Insert IPFS CID of final_proof.json once pinned)
- **SHA256 Hash:** `9646985581c825922ab085389a220a06e1486ff979f0332210c3aa15781b9a63`
- **OpenTimestamps Proof:** `final_proof.json.ots` (included in `/notarization/` folder)

---

## Bitcoin Blockchain Anchor

The notarization is permanently anchored to the Bitcoin blockchain.

- **Bitcoin Block Height:** `907234`
- **Block Explorer:** [View Block on Blockstream](https://blockstream.info/block/00000000000000000002b3017f50d0c4d3adbb72d6e18bc38d8dbb71c301a0df)
- **Primary Transaction ID:** [`de49fbe89fe9cf21baa95fc0aad9e3b486ce5eb2d4344c01a757c494f3a68d4e`](https://blockstream.info/tx/de49fbe89fe9cf21baa95fc0aad9e3b486ce5eb2d4344c01a757c494f3a68d4e)
- **Merkle Root:** `a5fccc19a381d866492e2769e668588e447be1c581fc002c555148ed5a102ba4`

This ensures the `final_proof.json` ledger existed as of the block timestamp and cannot be altered or forged.

---

## Associated Files (IPFS CIDs)

All core files referenced in the ledger:

- `sha256_of_ots.txt` — `bafkreiatpe3ckiqigzwtcbrzwrwex2f3lyyraqb2yqwqiwvginjfvjthve`
- `AIGO.zip.ots` — `bafkreih3lwqckxvvkuufhqn75y3qu3s7dnzjutw5cz62ap6pm2id5q3emq`
- `AIGO.zip` — `bafkreifeqz6duawsbw3xet7hqc2gy7u4vbir43m3j3gjatr7o6cwbhdxsm`
- `AIGO-txt_CID.ots` — `bafkreigu2cn3nhnnnzz42r7qsgglzmvwztae3twqaesbyjbpbuq336m3sm`
- `AIGO_CID.txt` — `bafkreia3vljkp6bec4pce3qnji2y77mpt3a2w6dpmpy3pjou4rfmtzwrfe`
- `AIGO.txt.ots` — `bafkreiexunhn372h7oupbtn6h43xowkgkcs56w4juwndp533tdczlagtgq`
- `AIGO.txt` — `bafkreiapko5o77dk4jfxe5n45qgrgfmjarcihqqgzsthaidm4ehykytdrm`

---

## How to Verify

1. **Verify via OpenTimestamps CLI (no Bitcoin node needed):**
   ```bash
   ots upgrade final_proof.json.ots
   ots verify final_proof.json.ots
   ```

2. **Check on Bitcoin Blockchain:**
   - Visit the [Block Explorer link](https://blockstream.info/block/00000000000000000002b3017f50d0c4d3adbb72d6e18bc38d8dbb71c301a0df).
   - Look for the transaction ID and confirm the Merkle root matches.

3. **Check via IPFS:**
   - Fetch the ledger and files using a public gateway, for example:  
     `https://ipfs.io/ipfs/<CID>` (replace `<CID>` with the ones listed above).

---

**Prepared by:** Ricky Foster (Symbiote001)  
**Date:** July 26, 2025  
**Purpose:** Establish immutable proof of authorship and existence for the AIGO whitepaper and related materials.
