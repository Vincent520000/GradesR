# GradesR
set.seed(7)
y <- rt(100,2)
hist(y, main=" ",
     col="seashell",
     prob=TRUE,
     xlab="x",
     cex.axis=1.25,
     cex.lab=1.5,
     mgp = c(2.75, 1, 0),
     breaks=16)
skewness(y)
kurtosis(y)

grades <- c(32, 39, 50, 53, 56, 58, 61, 63, 65, 66, 69, 70, 71, 73, 73, 74, 75, 76, 76, 76, 78, 78, 78, 81, 82, 84, 85, 86, 88, 89,  91, 98, 100)

hist(grades,
     freq=FALSE,
     main="Histogram of Grade Marks",
     xlab="Grades",
     breaks=14)
