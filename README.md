
# Rapport

**Skriv din rapport här!**

Först så skapades en cocnstraint layout vilket sedan blev fylld med en imageview, två textview och 
ett password, efter det så gavs alla views id namn och små tinkrade med text storlek och text.
Sedan så constrainades centrerat till mitten av skärmen genom användningen av 
layout_constraintEnd_toEndOf="parent" och layout_constraintStart_toStartOf="parent". Tillsammans så
centrerar constrainsten objectet i mitten av objektet den ligger i. sist så lades en margin top för
att allt skulle ligga längre ner på skärmen. Dem andra elementent har constraint top to bottom av 
objektet över dem.

```
<ImageView
            android:id="@+id/WelcomeImage"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            android:layout_marginTop="50sp"
            tools:srcCompat="@tools:sample/avatars" />
```

Bilder läggs i samma mapp som markdown-filen.
(det finns en bild, men den visas inte eftersom det är exempel bild)
![](![img.png](img.png))

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
