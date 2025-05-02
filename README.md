# **📖 ULTIMATE R (STATISTICS) README**  
**From Data Wrangling to Machine Learning**  

---

## **🔍 1. What is R?**  
### **Definition**  
R is a **programming language** for statistical computing, visualization, and machine learning.  

### **Key Features**  
- **Packages**: `ggplot2` (visualization), `dplyr` (data wrangling).  
- **RStudio IDE**: Code, plots, and data in one place.  

---

## **🛠 2. Installation**  
### **Step 1: Install R**  
- Download from [r-project.org](https://www.r-project.org/).  
- Install **RStudio** from [rstudio.com](https://www.rstudio.com/).  

---

## **📊 3. Basic Usage**  
### **Task: Linear Regression**  
```r  
data <- read.csv("data.csv")  
model <- lm(Sales ~ Marketing, data = data)  
summary(model)  
```  

### **Plotting with ggplot2**  
```r  
library(ggplot2)  
ggplot(data, aes(x=Marketing, y=Sales)) +  
  geom_point() +  
  geom_smooth(method="lm")  
```  

---

## **🚀 4. Advanced Techniques**  
### **Shiny Apps**  
```r  
library(shiny)  
ui <- fluidPage("Hello World")  
server <- function(input, output) {}  
shinyApp(ui, server)  
```  

### **Machine Learning (caret)**  
```r  
library(caret)  
model <- train(Species ~ ., data=iris, method="rf")  
``` 
