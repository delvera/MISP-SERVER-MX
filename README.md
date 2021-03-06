# MISP-SERVER-MX 


{
   "name": "gdpr",
   "expanded_name": "General Data Protection Regulation",
   "ref": [
      "http://eur-lex.europa.eu/legal-content/en/TXT/?uri=CELEX:32016R0679"
   ],
   "geographical_area": [
      "EU"
   ],
   "notice": [
      {
         "scope": ["attribute"],
         "field": ["category", "meta-category"],
         "value": [
            "Targeting data",
            "Attribution",
            "Financial fraud",
            "Social network",
            "Person"
         ],
         "tags": ["fpf:degrees-of-identifiability='explicitly-personal'"],
         "message": {
            "en": "This attribute is likely to contain personal data and the data subject is likely to be directly identifiable. Please verify that the processing of personal data is necessary and proportionate to the purposes (e.g. ensuring network and information security) and that you have a legal ground to share those personal data. Where applicable, please ensure that you have taken the necessary steps to ensure transparency towards the data subject in relation to the processing of their personal data."
         }
      },
      {
         "scope": ["attribute"],
         "field": ["category", "meta-category"],
         "value": [
            "Antivirus detection",
            "Payload delivery",
            "Artifacts dropped",
            "Payload installation",
            "Network activity",
            "External analysis",
            "Support tool"
         ],
         "tags": ["fpf:degrees-of-identifiability='potentially-identifiable'"],
         "message": {
            "en": "This attribute is likely to contain personal data and the data subject could be potentially directly identifiable. Please verify that the processing of personal data is proportionate to the purposes (e.g. ensuring network and information security) and that you have a legal ground to share those personal data. Where applicable, please ensure that you have taken the necessary steps to ensure transparency towards the data subjects in relation to the processing of their personal data."
         }
      },
      {
         "scope": ["attribute"],
         "field": ["category", "meta-category"],
         "value": [
            "Persistence mechanism",
            "Payload type",
            "Other"
         ],
         "tags": ["fpf:degrees-of-identifiability='not-readily-identifiable'"],
         "message": {
            "en": "This attribute is likely to contain personal data protected by additional safeguards and controls, but the data subject remains indirectly identifiable. Please verify that the processing of personal data is proportionate to the purposes (e.g. ensuring network and information security) and that you have legal ground to share those personal data."
         }
      },
      {
         "scope": ["attribute"],
         "field": ["category", "meta-category"],
         "value": [
            "Internal reference"
         ],
         "tags": ["fpf:pseudonymous-data='key-coded'"],
         "message": {
            "en": "This attribute may contain pseudonymised personal data, the data subject remaining indirectly identifiable. If personal data is contained, please ensure that the processing of personal data is proportionate to the purposes (e.g. ensuring network and information security) and that you have legal ground to share those personal data."
         }
      },
      {
         "scope": ["attribute"],
         "field": ["type"],
         "value": ["special-service-request"],
         "tags": [
            "gdpr:special-categories='genetic-data'",
            "gdpr:special-categories='health'"
         ],
         "message": {
            "en": "This attribute may contain special categories of sensitive personal data. If special categories of personal data are contained, please verify that the processing complies with GDPR Article 9 (2)"
         }
      },
	  {
         "scope": ["attribute"],
         "field": ["type"],
         "value": ["passenger-name-record"],
         "tags": [
            "gdpr:special-categories='racial-or-ethnic-origin'",
            "gdpr:special-categories='political-opinions'",
            "gdpr:special-categories='religious-or-philosophical-beliefs'",
            "gdpr:special-categories='trade-union-membership'",
            "gdpr:special-categories='health'"
         ],
         "message": {
            "en": "This attribute may contain special categories of sensitive personal data. If special categories of personal data are contained, please verify that your processing activity comply with Directive (EU) 2016/681 on the use of passenger name record (PNR) data for the prevention, detection, investigation and prosecution of terrorist offences and serious crime. Additionally please verify that the processing complies with GDPR Article 9 (2)"
         }
      },
      {
         "scope": ["attribute"],
         "field": ["type"],
         "value": ["email-attachment", "attachment", "malware-sample", "comment", "text", "other", "target-user", "threat actor"],
         "tags": [
            "gdpr:special-categories='racial-or-ethnic-origin'",
            "gdpr:special-categories='biometric-data'",
            "gdpr:special-categories='genetic-data'",
            "gdpr:special-categories='sex-life-or-sexual-orientation'",
            "gdpr:special-categories='health'",
            "gdpr:special-categories='political-opinions'",
            "gdpr:special-categories='religious-or-philosophical-beliefs'",
            "gdpr:special-categories='trade-union-membership'"
         ],
         "message": {
            "en": "This attribute may contain special categories of sensitive personal data. If special categories of personal data are contained, please verify that your processing activity complies with GDPR Article 9 (2)"
         }
      }
   ]
}
?? 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Bl
