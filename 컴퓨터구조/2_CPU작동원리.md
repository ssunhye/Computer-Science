# ๐ก CPU ์๋ ์๋ฆฌ ๐ก

## ๐ CPU?
```
CPU๋ ์ปดํจํฐ์์ ๊ฐ์ฅ ํต์ฌ์ ์ธ ์ญํ ์ ์ํํ๋ ๋ถ๋ถ.
'์ธ๊ฐ์ ๋๋'
์ฐ์ฐ์ฅ์น, ์ ์ด์ฅ์น, ๋ ์ง์คํฐ 3๊ฐ์ง๋ก ๊ตฌ์ฑ๋จ
```

## ๐ CPU์ ๊ตฌ์ฑ
* `์ฐ์ฐ์ฅ์น`: ์ฐ์  ์ฐ์ฐ๊ณผ ๋ผ๋ฆฌ ์ฐ์ฐ์ ์ํ   
์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ๋ฅผ ๋ ์ง์คํฐ์์ ๊ฐ์ ธ์ค๊ณ , ์ฐ์ฐ ๊ฒฐ๊ณผ๋ฅผ ๋ค์ ๋ ์ง์คํฐ๋ก ๋ณด๋ด ์ ์ฅ.

* `์ ์ด์ฅ์น`: ๋ช๋ น์ด๋ฅผ ์์๋๋ก ์คํํ  ์ ์๋๋ก ์ ์ด   
์ฃผ๊ธฐ์ต์ฅ์น์์ ํ๋ก๊ทธ๋จ ๋ช๋ น์ด๋ฅผ ๊บผ๋ด ํด๋   
๊ทธ ๊ฒฐ๊ณผ์ ๋ฐ๋ผ ๋ช๋ น์ด ์คํ์ ํ์ํ ์ ์ด ์ ํธ๋ฅผ ๊ธฐ์ต์ฅ์น, ์ฐ์ฐ์ฅ์น, ์์ถ๋ ฅ์ฅ์น๋ก ๋ณด๋.   
๋ณด๋ธ ์ ํธ๋ฅผ ๋ฐ์ ๋ค์์ ์ํํ  ๋์ ๊ฒฐ์ .

* `๋ ์ง์คํฐ`: ๊ณ ์๊ธฐ์ต์ฅ์น๋ก ๋ช๋ น์ด ์ฃผ์, ์ฝ๋, ์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ, ์ฐ์ฐ ๊ฒฐ๊ณผ ๋ฑ์ ์์๋ก ์ ์ฅ   
    - ๋ฒ์ฉ ๋ ์ง์คํฐ: ์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ๋ ์ฐ์ฐ ๊ฒฐ๊ณผ๋ฅผ ์์๋ก ์ ์ฅํ๋ ๋ ์ง์คํฐ 
    - ํน์ ๋ ์ง์คํฐ: ํน๋ณํ ์ฉ๋๋ก ์ฌ์ฉํ๋ ๋ ์ง์คํฐ. ์ฉ๋์ ๊ธฐ๋ฅ์ ๋ฐ๋ผ ๊ตฌ๋ถ   
    ```
        - MAR (๋ฉ๋ชจ๋ฆฌ ์ฃผ์ ๋ ์ง์คํฐ): ์ฝ๊ธฐ์ ์ฐ๊ธฐ ์ฐ์ฐ์ ์ํํ  ์ฃผ๊ธฐ์ต์ฅ์น ์ฃผ์ ์ ์ฅ
        - PC (ํ๋ก๊ทธ๋จ ์นด์ดํฐ): ๋ค์์ ์ํํ  ๋ช๋ น์ด ์ฃผ์ ์ ์ฅ
        - IR (๋ช๋ น์ด ๋ ์ง์คํฐ): ํ์ฌ ์คํ ์ค์ธ ๋ช๋ น์ด ์ ์ฅ
        - MBR(๋ฉ๋ชจ๋ฆฌ ๋ฒํผ ๋ ์ง์คํฐ): ์ฃผ๊ธฐ์ต์ฅ์น์์ ์ฝ์ด์จ ๋ฐ์ดํฐ or ์ ์ฅํ  ๋ฐ์ดํฐ ์์ ์ ์ฅ
        - AC (๋์ฐ๊ธฐ): ์ฐ์ฐ ๊ฒฐ๊ณผ ์์ ์ ์ฅ
    ```

## ๐ CPU ๋์
1. **์ฃผ๊ธฐ์ต์ฅ์น**๋ ์๋ ฅ์ฅ์น์์ ์๋ ฅ๋ฐ์ ๋ฐ์ดํฐ ๋๋ ๋ณด์กฐ๊ธฐ์ต์ฅ์น์ ์ ์ฅ๋ ํ๋ก๊ทธ๋จ์ ์ฝ์ด์จ๋ค.
2. ์ค์์ฒ๋ฆฌ์ฅ์น๋ ํ๋ก๊ทธ๋จ์ ์คํํ๊ธฐ ์ํด ์ฃผ๊ธฐ์ต์ฅ์น์ ์ ์ฅ๋ **ํ๋ก๊ทธ๋จ ๋ช๋ น์ด**์ **๋ฐ์ดํฐ**๋ฅผ ์ฝ์ด์ ์ฒ๋ฆฌํ๊ณ     
๊ฒฐ๊ณผ๋ฅผ ๋ค์ ์ฃผ๊ธฐ์ต์ฅ์น์ ์ ์ฅ
3. ์ฃผ๊ธฐ์ต์ฅ์น๋ ์ฒ๋ฆฌ ๊ฒฐ๊ณผ๋ฅผ ๋ณด์กฐ๊ธฐ์ต์ฅ์น์ ์ ์ฅํ๊ฑฐ๋ ์ถ๋ ฅ์ฅ์น๋ก ๋ณด๋
4. **์ ์ด์ฅ์น**๋ 1~3์์ ๋ช๋ น์ด๊ฐ ์์๋๋ก ์คํ๋๋๋ก ๊ฐ ์ฅ์น ์ ์ด

<img src = "/์ปดํจํฐ๊ตฌ์กฐ/img/cpu.jpg" width="500px">

#### ์ธ์ถ ์ฌ์ดํด์ ๋ง์ดํฌ๋ก์ฐ์ฐ
```
T0: MAR <- PC
T1: MBR <- M[MAR], PC <- PC + 1
T2: IR <- MBR
```
PC์ ์ง์ ๋ ์ฃผ์๋ฅผ MAR๋ก ์ ๋ฌ.
MAR์ ์ ์ฅ๋ ๋ด์ฉ์ ํ ๋๋ก ์ฃผ๊ธฐ์ต์ฅ์น์ ํด๋น ์ฃผ์์์ ๋ช๋ น์ด ์ธ์ถ
์ธ์ถํ ๋ช๋ น์ด๋ฅผ MBR์ ์ ์ฅ

**๋ค์ ๋ช๋ น์ด ์ธ์ถ์ ์ํด `PC(ํ๋ก๊ทธ๋จ์นด์ดํฐ)` ๊ฐ ์ฆ๊ฐ**

MBR(๋ฉ๋ชจ๋ฆฌ ๋ฒํผ ๋ ์ง์คํฐ)์ ์ ์ฅ๋ ๋ด์ฉ์ IR(๋ช๋ น์ด ๋ ์ง์คํฐ)์ ์ ๋ฌ.

#### ADD Addr๋ช๋ น์ด ์ฐ์ฐ
```
T0: MAR <- IR(Addr)
T1: MBR <- M[MAR]
T2: AC <- AC + MBR
```
๋ฉ๋ชจ๋ฆฌ์ ์ ์ฅ๋ ๋ฐ์ดํฐ ๊ฐ์ MBR์ ์ ์ฅ
IR์ MBR์ ๊ฐ์ด ์ด๋ฏธ ์ ์ฅ๋ ์ํ์ด๊ธฐ ๋๋ฌธ์ PC <- PC + 1 ๋ช๋ น์ด๋ ํ์ํ์ง ์์.
AC์ MBR์ ๋ํ ๊ฐ ์ ์ฅ.


## ๐ ์ฉ์ด์ ๋ฆฌ
> `์ค์์ฒ๋ฆฌ์ฅ์น CPU`   
> ์ธ๊ฐ์ผ๋ก ๋ฐ์ง๋ฉด ๋๋์ ํด๋นํ๋ ๋ถ๋ถ   
> ์ฃผ๊ธฐ์ต์ฅ์น์์ ํ๋ก๊ทธ๋จ ๋ช๋ น์ด์ ๋ฐ์ดํฐ๋ฅผ ์ฝ์ด์ ์ฒ๋ฆฌํ๊ณ  ๋ช๋ น์ด์ ์ํ ์์๋ฅผ ์ ์ดํจ   
> - ์ค์์ฒ๋ฆฌ์ฅ์น๋ ๋น๊ต์ ์ฐ์ฐ์ ๋ด๋นํ๋ **์ฐ์ ๋ผ๋ฆฌ์ฐ์ฐ์ฅ์น(ALU)** ์   
> - ๋ช๋ น์ด์ ํด์๊ณผ ์คํ์ ๋ด๋นํ๋ **์ ์ด์ฅ์น**,   
> - ์๋๊ฐ ๋น ๋ฅธ ๋ฐ์ดํฐ ๊ธฐ์ต์ฅ์์ธ **๋ ์ง์คํฐ**๋ก ๊ตฌ์ฑ      
> ๊ฐ์ธ์ฉ ์ปดํจํฐ์ ๊ฐ์ ์ํ ์ปดํจํฐ์์๋ CPU๋ฅผ ๋ง์ดํฌ๋กํ๋ก์ธ์๋ผ๊ณ  ๋ถ๋ฆ

> `์ฐ์ฐ์ฅ์น`   
> ์ฐ์  ์ฐ์ฐ๊ณผ ๋ผ๋ฆฌ ์ฐ์ฐ์ ์ํ   
> ์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ๋ฅผ ๋ ์ง์คํฐ์์ ๊ฐ์ ธ์ค๊ณ , ์ฐ์ฐ ๊ฒฐ๊ณผ๋ฅผ ๋ค์ ๋ ์ง์คํฐ๋ก ๋ณด๋ด ์ ์ฅ.   

> `์ ์ด์ฅ์น`   
> ๋ช๋ น์ด๋ฅผ ์์๋๋ก ์คํํ  ์ ์๋๋ก ์ ์ด   
> ์ฃผ๊ธฐ์ต์ฅ์น์์ ํ๋ก๊ทธ๋จ ๋ช๋ น์ด๋ฅผ ๊บผ๋ด ํด๋   
> ๊ทธ ๊ฒฐ๊ณผ์ ๋ฐ๋ผ ๋ช๋ น์ด ์คํ์ ํ์ํ ์ ์ด ์ ํธ๋ฅผ ๊ธฐ์ต์ฅ์น, ์ฐ์ฐ์ฅ์น, ์์ถ๋ ฅ์ฅ์น๋ก ๋ณด๋.   
> ๋ณด๋ธ ์ ํธ๋ฅผ ๋ฐ์ ๋ค์์ ์ํํ  ๋์ ๊ฒฐ์ .   

> `๋ ์ง์คํฐ`   
> ๊ณ ์๊ธฐ์ต์ฅ์น๋ก ๋ช๋ น์ด ์ฃผ์, ์ฝ๋, ์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ, ์ฐ์ฐ ๊ฒฐ๊ณผ ๋ฑ์ ์์๋ก ์ ์ฅ   
> > `๋ฒ์ฉ ๋ ์ง์คํฐ`   
> > ์ฐ์ฐ์ ํ์ํ ๋ฐ์ดํฐ๋ ์ฐ์ฐ ๊ฒฐ๊ณผ๋ฅผ ์์๋ก ์ ์ฅํ๋ ๋ ์ง์คํฐ   
> > `ํน์ ๋ ์ง์คํฐ`   
> > ํน๋ณํ ์ฉ๋๋ก ์ฌ์ฉํ๋ ๋ ์ง์คํฐ. ์ฉ๋์ ๊ธฐ๋ฅ์ ๋ฐ๋ผ ๊ตฌ๋ถ   
> > > `MAR (๋ฉ๋ชจ๋ฆฌ ์ฃผ์ ๋ ์ง์คํฐ)`   
> > > ์ฝ๊ธฐ์ ์ฐ๊ธฐ ์ฐ์ฐ์ ์ํํ  ์ฃผ๊ธฐ์ต์ฅ์น ์ฃผ์ ์ ์ฅ   
> > > `PC (ํ๋ก๊ทธ๋จ ์นด์ดํฐ)`   
> > > ๋ค์์ ์ํํ  ๋ช๋ น์ด ์ฃผ์ ์ ์ฅ   
> > > `IR (๋ช๋ น์ด ๋ ์ง์คํฐ)`   
> > > ํ์ฌ ์คํ ์ค์ธ ๋ช๋ น์ด ์ ์ฅ   
> > > `MBR(๋ฉ๋ชจ๋ฆฌ ๋ฒํผ ๋ ์ง์คํฐ)`   
> > > ์ฃผ๊ธฐ์ต์ฅ์น์์ ์ฝ์ด์จ ๋ฐ์ดํฐ or ์ ์ฅํ  ๋ฐ์ดํฐ ์์ ์ ์ฅ   
> > > `AC (๋์ฐ๊ธฐ)`   
> > > ์ฐ์ฐ ๊ฒฐ๊ณผ ์์ ์ ์ฅ   