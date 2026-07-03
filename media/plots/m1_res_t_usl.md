ggplot(m1_data, aes(x=Temperature, y=PartResistance)) + geom_boxplot() + geom_hline(yintercept=10)
