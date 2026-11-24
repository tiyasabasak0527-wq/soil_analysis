SOIL FERTILITY CLASSIFICATION — 1000-INSTANCE PBL DATASET

STATUS: SOURCE-CALIBRATED SYNTHETIC TEACHING DATA.
These 1,000 rows are generated for BCA PBL and are NOT 1,000 copied/authentic laboratory observations.

AUTHENTIC SOURCE BASIS
AgriNet (Mendeley Data, DOI 10.17632/c7tr9j78td.1): 258 laboratory-tested Bareilly, Uttar Pradesh
soil records containing pH, EC, OC, available N, P, K, S, Zn, B, Fe, Mn and Cu.
Krishnagiri raw soil dataset (Mendeley Data, DOI 10.17632/7bk36mh3tc.1): 125 laboratory-tested
samples analyzed for pH, EC, texture, SOC and available NPK.
Dharmapuri soil data article: 125 laboratory-tested samples including pH, EC, soil separates,
OC, N, P and K.

TARGET LABEL
Fertility_Class is DERIVED for teaching, not an original field-measured label.
Score combines N, P, K, organic carbon, pH and EC:
Low <40; Medium 40–69.99; High >=70.

STUDENT USE
Inspect provenance; clean data; handle missing values; perform EDA/correlation; select features;
compare Decision Tree, Random Forest, KNN and SVM; use stratified splitting; report accuracy,
precision, recall, F1 and confusion matrix; examine feature importance; build a prediction UI.

SCIENTIFIC CAUTION
Do not state that this file contains 1,000 authentic measured soil samples. For publication,
replace these synthetic rows with underlying authentic records and retain original provenance.
