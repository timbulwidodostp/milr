# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Maximum likelihood estimation of multiple-instance logistic regression with LASSO penalty Use milr With (In) R Software
install.packages("milr")
library("milr")
milr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/milr/main/milr/milr.csv",sep = ";")
# Estimation Maximum likelihood estimation of multiple-instance logistic regression with LASSO penalty Use milr With (In) R Software
milr$X = cbind(milr$X.1,milr$X.2,milr$X.3,milr$X.4)
milr <- milr(milr$Z, milr$X, milr$ID)
summary(milr)
# Maximum likelihood estimation of multiple-instance logistic regression with LASSO penalty Use milr With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished