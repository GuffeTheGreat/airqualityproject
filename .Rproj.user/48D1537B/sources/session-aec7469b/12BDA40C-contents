# 


  qt(0.975,9)
  
  h <- c(168,161,167,179,184,166,198,187,191,179)
  
  h_mean = mean(h)
  
  sum(h)/mean(h)
  n = length(h)
  t_value = qt(1-0.05/2,length(h)-1,) 
  se = sd(h) / sqrt(n)
  min = h_mean - t_value * se
  print(min)
  
  max = h_mean + t_value * se
  print(max)
  
  t.test(h,conf.level=0.95)

                                                                                  #   # Load Data
# data <- read.table("AirQualityUCI.csv", header = TRUE, sep = ";",dec = ",")
# 
#   # Construct Dataframe
# dataframe <- data.frame(
#   id = c(0:9470),
#   date = data$Date,
#   kumulativedate = c(0:9470),
#   time = data$Time,
#   cogt = data$CO.GT,
#   no2gt = data$NO2.GT.
# )
# 
# #DataCleanUp ---
# 
#  #Remove Invalid Data
#  dataframe <- dataframe[dataframe$time >= 0, ] 
#  
#  
#  #MakeDateCumulative
#   date1string <- "10/03/2004"
#   date1 <-  strptime(as.character(date1string), "%d/%m/%Y")
#   resultater <- numeric(nrow(dataframe))
#   for (i in 1:nrow(dataframe)) {
#     date2string <- dataframe$date[i]
#     date2 <-  strptime(as.character(date2string), "%d/%m/%Y")
#     resultater[i] <-  difftime(date2,date1, units = "days")
#   }
#   dataframe$dayssince <- resultater
#  
# 
#  # Convert time from String to Integer
#  dataframe$time <- gsub(".00.00", "", dataframe$time)
#  dataframe$time <- as.numeric(dataframe$time)
#  
#  # Filtrer rækker med fejlværdier
#  dataframe <- dataframe[dataframe$cogt != -200.0, ]
#  dataframe <- dataframe[dataframe$no2gt != -200.0, ]
#  
#  #Plot Data
#  plot(dataframe$kumulativedate, dataframe$cogt,
#         xlab = "X Axis",
#          ylab = "Y Axis",
#          main = "Name")
#  
#  
# # hod <- data1$Time
# # print(hod)
# #quantile(data$CO.GT.)
# # plot(data$Hour.,data$NOx.GT.)
# 
