# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Cochran's Q Test Use cochran_qtest (rstatix) With (In) R Software
install.packages("rstatix")
library("rstatix")
cochran_qtest = read.csv("https://raw.githubusercontent.com/timbulwidodostp/cochran_qtest/main/cochran_qtest/cochran_qtest.csv",sep = ";")
# Estimation Cochran's Q Test Use cochran_qtest (rstatix) With (In) R Software
cochran_qtest <- cochran_qtest(cochran_qtest, outcome ~ treatment|participant)
cochran_qtest
# Cochran's Q Test Use cochran_qtest (rstatix) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished