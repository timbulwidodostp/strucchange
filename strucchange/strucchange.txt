# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Structural change tests (chow test) in linear regression models Use sctest (strucchange) With R Software
install.packages("strucchange")
library("strucchange")
strucchange = read.csv("https://raw.githubusercontent.com/timbulwidodostp/strucchange/main/strucchange/strucchange.csv",sep = ";")
# Estimation Structural change tests ( chow test) in linear regression models Use sctest (strucchange) With R Software
strucchange <- sctest(Employed ~ Year + GNP.deflator + GNP + Armed.Forces, data = strucchange, type = "Chow", point = 7)
print(strucchange)
# Structural change tests (chow test) in linear regression models Use sctest (strucchange) With R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished