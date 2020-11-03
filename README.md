# Attribute-driven-Capsule-Network-for-Entity-Relation-Prediction
CompanyRelationCollection (CRC) refers to company entities and BlurbGenreCollection(BGC) refers to book entities. 

The CRC is a chinese company entity dataset that collected from the Internet. It consists of 58,013 company entities and there are 6 common attributes for each company entity, which includes company_name, company_address, company_type, industry_category, business_scope and abstract. For a pair of company entities, there exists three major links content, which includes customer(C), provider(P), rival(R).

The BGC is an english public dataset. It includes 91,892 book entities and each entity has 3 common attributes. We define three kinds of link according to book categories, which includes similar(S), presumably-similar(P), dissimilar(D). 


# Multi-label Classification of Long Text Based onKey-sentences Extraction
 CompanyCategoryDataset(CCD): We construct a  dataset of company entities from online open source data1, where each company entity may have multiple industry category labels. 
 
 The dataset includes 12492 company entities and 17 labels. Each company entity have company_name, industry_category,abstract common text attributes. We use company_name and abstract to form a document-level text for multiple industry category prediction, where the average length of the texts is 604, and the maximum length is 4294.
