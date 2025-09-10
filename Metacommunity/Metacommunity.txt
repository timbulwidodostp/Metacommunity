# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Analysis of the Elements of Metacommunity Structure Use Metacommunity (metacom) With (In) R Software
install.packages("metacom")
library("metacom")
Metacommunity = read.csv("https://raw.githubusercontent.com/timbulwidodostp/Metacommunity/main/Metacommunity/Metacommunity.csv",sep = ";")
# Estimation Analysis of the Elements of Metacommunity Structure Use Metacommunity (metacom) With (In) R Software
Metacommunity <- Metacommunity(Metacommunity, method='r1', sims=100, scores=1)
Metacommunity
# Analysis of the Elements of Metacommunity Structure Use Metacommunity (metacom) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished