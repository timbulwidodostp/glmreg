# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a GLM with lasso (or elastic net), snet or mnet regularization Use glmreg With (In) R Software
install.packages("mpath")
library("mpath")
glmreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/glmreg/main/glmreg/glmreg.csv",sep = ";")
# Estimation Fit a GLM with lasso (or elastic net), snet or mnet regularization Use glmreg With (In) R Software
glmreg <- glmreg(Dependen ~ Independen_1 + Independen_2, data = glmreg)
coef(glmreg)
# Fit a GLM with lasso (or elastic net), snet or mnet regularization Use glmreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished