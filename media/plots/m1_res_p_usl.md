ggplot(m1_data, aes(x=Pressure, y=PartResistance)) + geom_boxplot() + geom_hline(yintercept=10)
