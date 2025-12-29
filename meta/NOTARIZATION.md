# Civic Overwatch — NOTARIZATION.md

This file records external timestamping / notarization events for the Civic Overwatch standard.

## 1. Hash surface

The current canonical hash surface is defined in:

- `meta/HASHES.md`

Only the files listed there are considered canonical for v1.0.

## 2. Timestamping (e.g., OpenTimestamps)

When you notarize this hash set with a service such as **OpenTimestamps (OTS)**:

1. Use the `meta/HASHES.md` file as the input for the timestamp.  
2. Save the resulting `.ots` receipt file into a suitable path, for example:

   - `meta/ots_receipts/Civic_Overwatch_HASHES_v1.0.ots`

3. Record the event below.

### 2.1 OTS receipts

- *(placeholder — fill after notarization)*  
  - Date:  
  - Tool / service: OpenTimestamps  
  - Input file: `meta/HASHES.md`  
  - Receipt path: `meta/ots_receipts/Civic_Overwatch_HASHES_v1.0.ots`

## 3. Additional notarization methods (optional)

You MAY also:

- mirror the hash or OTS commitment in other chains or registries,  
- include the hash in legal or organizational records,  
- or embed it in public disclosures.

Record any such use here with:

- date,  
- method,  
- reference / transaction ID,  
- and scope (what was being anchored).
