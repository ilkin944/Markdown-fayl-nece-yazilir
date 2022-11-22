# Markdown faylı necə yaradılmalıdır? Markodown faylında hansı yazılış üsulları var?

# Mətnlər
```
# Başlıqlar
```
Başlıq yaratmaq üçün #başlıq mətnindən əvvəl heş (dies və ya türmə :D) simvol əlavə edin. İstifadə etdiyiniz nömrə #başlığın ölçüsünü müəyyən edəcək.

Məsələn:
# Ən böyük başlıq və tək diesdən istifadə edə bilərsiniz :point_down:
```
# Başlıqlar
```
## İkinci böyük başlıqdır və iki diesdən istifadə edə bilərsiniz :point_down:
```
## Başlıqlar
```
### Üçüncü başlıqdır və üç diesdən istifadə edə bilərsiniz :point_down:
```
### Başlıqlar
```
#### Dördüncü başlıqdır və dörd diesdən istifadə edə bilərsiniz :point_down:
```
#### Başlıqlar
```
##### Beşinci başlıqdır və beş diesdən istifadə edə bilərsiniz :point_down:
```
##### Başlıqlar
```
###### Altıncı başlıqdır və altı diesdən istifadə edə bilərsiniz :point_down:
```
###### Başlıqlar
```


- **Qalın mətnlər yazmaq üçün, mətnimizin əvvəlinə və sonuna 2 ədəd ulduz simvolu (və ya 2 ədəd altdan xətt simvolu) əlavə edirik** :point_down:
```
**Qalın mətn**
```
- *İtalik mətnlər yazmaq üçün, mətnimizin əvvəlinə və sonuna 1 ədəd ulduz simvolu (və ya 1 ədəd altdan xətt simvolu)  əlavə edirik* :point_down:
```
*İtalik mətn*
```
- ~~Mətnlərimizin ortasında xətt çəkilməsi üçün mətnin əvvəlinə və sonuna 2 ədəd dalğalı defis əlavə edirik~~
```
~~Ortadan xətt~~
```

- **Bu mətn həm qalın _həmdə  italikdir (əvvəlində və sonunda altdan xətt)_**:point_down:
```
- **Bu mətn həm qalın _həmdə  italikdir (əvvəlində və sonunda altdan xətt)_** 
```

- ***Bu mətnin hər bir simvolu isə həm qalın həm də italikdir ( bunun üçün cümləmin hər iki tərəfinə 3 ulduz əlavə etməliyəm)*** :point_down:
```
***Bu mətnin hər bir simvolu isə həm qalın həm də italikdir ( bunun üçün cümləmin hər iki tərəfinə 3 ulduz əlavə etməliyəm)*** 
```

- <sub>bu alt yazıdır (alt yazı yazmaq üçün htmldəki sub teqindən istifadə etmək lazımdır)</sub> :point_down:
```
<sub>bu alt yazıdır (alt yazı yazmaq üçün htmldəki sub teqindən istifadə etmək lazımdır)</sub>
```


- <sup>bu üst yazıdır (üst yazı yazmaq üçün htmldəki sup teqindən istifadə etmək lazımdır)</sup> :point_down:
```
<sup>bu üst yazıdır (üst yazı yazmaq üçün htmldəki sup teqindən istifadə etmək lazımdır)</sup>
```


> Burada sitat gətirdik (Sitat üçün > işarəsindən istifadə etmək lazımdır)

### Yeni bir repo yaradarkən bu əmrlərə ehtiyacımız var (bu bölməni yarada bilmək üçün ümumi cümləmin əvvəlin və sonuna 3  əyri dırnaq ``` əlavə edirik): :point_down:
``` 
touch README.md
git status 
git add --all (və ya -A və yaxud da git add .)
git commit -m "Kommitiniz"
git remote add origin "url"
git push -u origin master
```

# Rənglər
#### sözlərə arxa fon rəngi verə bilmək üçün isə rəng kodlarımızı (hex, rgb və hsl) əyri dırnaq içərisində yaza bilərik`#0969DA` :point_down:

# Linklər

#### Əgər README-ə hər hansısa link [daxil etmək](https://www.instagram.com/rgacademy_org) istəyirsinizsə link sözümüzü kvadrat mötərizə daxilində, gedəcəyimiz ünvanı isə normal mötərizə daxilində edə bilərik :point_down:

#### Hər hansı faylı referans olaraq bildirmək istəyirsinizsə kvadrat mötərizə daxilində sözü, normal mötərizələrdə isə faylın ünvanını bildirə bilərsiniz. Məsələn [bu yazının istinad mənbəsi](/MENBE.md) :point_down:


# Şəkillər
#### README-ə şəkil əlavə etmək üçün link əlavə etmə üsulunun əvvəlinə ! simvolu daxil etmək lazımdır ![](). Məsələn:
![RG Academy Logo](./img/RG%20Agency%20Logo%20v2022.png)   :point_down:

#### Həmçinin əlavə etdiyiniz şəklin light/dark moda əsasən dəyişməsini də təmin edə bilərsiniz. Bunun üçün HTML-dəki bu kodlardan istifadə etmək lazımdır: :point_down:
```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/img/RG Academy Logo arxa fonu rəngli 1x1.png">
  <source media="(prefers-color-scheme: light)" srcset="/img/rg agency logo1.png">
  <img alt="RG Agency Logo." src="/img/RG Agency Logo v2022.png">
</picture>
```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/img/RG Academy Logo arxa fonu rəngli 1x1.png">
  <source media="(prefers-color-scheme: light)" srcset="/img/rg agency logo1.png">
  <img alt="RG Agency Logo." src="/img/RG Agency Logo v2022.png">
</picture>


# Siyahılar
#### Sayıla bilinməyən siyahılar (ul və li) yaratmaq üçün -,+,* simvollarından istifadə edə bilərsiniz . :point_down:

- HTML
* CSS
+ JS
```
- HTML
* CSS
+ JS
```

#### Sayıla bilinən siyahılar (ol və li) yaratmaq üçün rəqəmlərdən istifadə edə bilərsiniz . :point_down:

1. HTML
2. CSS
3. JS
```
1. HTML
2. CSS
3. JS
```

#### Siyahı bəndləri üçün isə bir tab qədər məsafə qoyub yaza bilərsiniz :point_down:
1. HTML
2. CSS
    - Flex
3. JS
    - Events
    - DOM
    - Framework
        - JQuery
    - Library
        - React
        - Angular
        - Vue
```
1. HTML
2. CSS
    - Flex
3. JS
    - Events
    - DOM
    - Framework
        - JQuery
    - Library
        - React
        - Angular
        - Vue
```

### Tapşırıq siyahıları
#### Tapşırıqlar siyahısı yaratmaq üçün siyahı elementlərinə defis və boşluq və ardınca daxil olan ön söz yazın [ ]. Tapşırığı tamamlanmış kimi qeyd etmək üçün istifadə edin [x]. :point_down:

- [x] #README əlavə edildi
- [ ] Dəstək olundu
- [ ] Repo-nu hər kəs ulduzladı :star_struck:

```
- [x] #README əlavə edildi
- [ ] Dəstək olundu
- [ ] Repo-nu hər kəs ulduzladı :star_struck:
```


# Digər
### İnsanları və komandaları qeyd etmək
#### GitHub- da istifadəçi və ya komandanın adını əlavə edərək şəxsi və ya komandanı qeyd edə bilərsiniz . @ simvolu bu, bildirişi işə salacaq və onların diqqətini söhbətə cəlb edəcək. İstifadəçi adını və ya komanda adını qeyd etmək üçün şərhə düzəliş etsəniz, insanlar da bildiriş alacaqlar.
@github/support Azərbaycan dilində məqalənizi yeniləmək istərdiniz? 
```
@github/support Azərbaycan dilində məqalənizi yeniləmək istərdiniz? 
```