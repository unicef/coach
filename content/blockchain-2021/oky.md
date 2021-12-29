---
title: Oky
layout: dpg-report
dpg_report:
    req1:
        status: 1
        context: ["3", "5", "6"]
        evidence: "[DPG Registry](https://digitalpublicgoods.net/registry/oky.html)"
    req2:
        status: 1
        context: ["AGPL-3.0", "CC BY 4.0"]
        evidence: "[GitHub](https://github.com/alextyers/period-tracker-app-whitelabelled/blob/main/LICENSE)"
    req3:
        status: 1
        context: ["yes"]
        evidence: "http://okyapp.info/"
    req4:
        status: 1
        context: ["no"]
        evidence: "not applicable"
    req5:
        status: 2
        context: ["Repo README", "Google Docs"]
        evidence: "[Google Docs](https://drive.google.com/open?id=1iXM8tBPdsnLciG1Pw2eFJN4zq3TsKpEA)"
    req6:
        status: 2
        context: ["yes"]
        evidence: "All non-PII data is stored in a postgress SQL database and can be exported in standard CSV or SQL statement formats on demand. However, Oky has strict data governance processes in place, and access is very restricted."
    req7:
        status: 2
        context: ["GDPR"]
        evidence: "[Privacy policy](https://docs.google.com/document/d/16lW1SV-DrO4XsninP_SsMj424RDcCOapG96BS0OxSoo/preview), [terms and conditions](https://docs.google.com/document/d/1zN_YF5Mae13uEAljoZnsisoX_5C9SFaaCiOf2ZfFRNk/preview)"
    req8:
        status: 3
        context: ["yes"]
        evidence: "REST, JSON, CSV. [GitHub](https://github.com/alextyers/period-tracker-app-whitelabelled)"
    req9:
        status: 2
        context: ["yes"]
        evidence: "The Oky app has been designed with very high privacy settings, to protect users. We do not hold in our database any personally identifiable data. While user-generated fields at time of registration (username, password, secure answer) are not able to identify an individual, as part of Oky’s strict data governance approach, Oky hashes and salts these fields to render the original values inaccessible. This hashing approach is used with the purpose to: (a) obfuscate the username to anyone who might access the database, and (b) to guarantee user authentication, ie. to allow users to log into their account on the same device or a different device."
    req9a:
        status: 3
        context: ["does not collect PII"]
        evidence: "not applicable"
    req9b:
        status: 1
        context: ["does not store content"]
        evidence: "not applicable"
    req9c:
        status: 2
        context: ["no interactions among users and contributors"]
        evidence: "not applicable"

---

A grid will be shown here for Oky's progress to becoming a DPG.
