




```
r language BS20, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis granülamatöz hepatit, Tbc vs anti-Tbc ilaç etkisi TR, echo = (language == "TR")
## BS20 - granülamatöz hepatit, Tbc vs anti-Tbc ilaç etkisi {#sec-BS20 }
```


```
asis granulamatous hepatitis, Tbc vs anti-Tbc drug induced reaction EN, echo = (language == "EN")
## BS20 - granulamatous hepatitis, Tbc vs anti-Tbc drug induced reaction {#sec-BS20 }
```






```
r BS20 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS20-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS20/HE.html",
  file = "./screenshots/BS20-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS20/HE.html](https://images.patolojiatlasi.com/BS20/HE.html)





```
asis, echo = (language == "TR")

**granülamatöz hepatit, Tbc vs anti-Tbc ilaç etkisi**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS20-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS20/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS20/HE.html)
```

```
asis, echo = (language == "EN")

**granulamatous hepatitis, Tbc vs anti-Tbc drug induced reaction**

[![Click for Full Screen WSI](./screenshots/BS20-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS20/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS20/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS20/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS20/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

granülamatöz hepatit, Tbc vs anti-Tbc ilaç etkisi

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

granulamatous hepatitis, Tbc vs anti-Tbc drug induced reaction

:::

```









:::::







