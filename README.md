# Bioinfo1_jwb
Works for classroom : "Bio-infomatics and practice 1" in Seoul Nat'l Univ. 


<span style="color:blue"> 파란 밑줄 </span>
로 된 링크를 따라, 해당 미션을 확인 가능합니다.

[ 2023-20920 Woobeen Jeong / interdisciplinary program in bio-infomatics ]

## Content 1: LIN28A RNA interaction
* 2023-04-28 **[ Mission 1 ]**
  > what and why does it bind
  
  > RNA-seq의 applied version인 Ribosome seq과 CLIP-seq 결과물을 바탕으로 *Lin28a* knockdown한 cell에서 두 관측결과의 상관관계를 파악한다. 핵심 역량은 1)Ribo-seq과 CLIP-seq의 이해 2)Normalization 3)Cutoff설정

  <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/7ca151d3-76b6-4f95-aecd-c722d0416f04" alt="image" width="auto" height="100">
  </p>

   [> Mission 1:](https://github.com/WoobeenJeong/bioinfo1_jwb/blob/main/CoLab_TermProj_2023_1.ipynb)
   [file name] CoLab_TermProj_2023_1.ipynb
 
  <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/76811af1-eac4-4fc0-b506-7267fd12e05e" alt="image" width="auto" height="100">
  </p>
   
   [> Not a Mission 1.5:](https://github.com/WoobeenJeong/bioinfo1_jwb/blob/main/CoLab_TermProj_2023_1_5.ipynb)
   [file name] CoLab_TermProj_2023_1_5.ipynb

* 2023-05-05 **[ Mission 2 ]**
  > Ribosomal footprint density near start and stop codons
  
  > Translation region을 확인하는 Ribosome-seq을 바탕으로 start와 stop가까이에 얼마나 많은 read가 align되었는지를 파악한다. 특히 3 nucleotide단위로 읽기때문에 첫 peak가 높고 이후로 줄어드는 그림의 특징을 인지한다. 
 
  <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/cb6520ea-825e-4c50-96fd-2c9de0f7a3df" alt="image" width="auto" height="100">
   </p>
  
   [> Mission 2:](https://github.com/WoobeenJeong/bioinfo1_jwb/blob/main/CoLab_TermProj_2023_2.ipynb)
   [file name] CoLab_TermProj_2023_2.ipynb

* 2023-05-12
  > 
  
  file name:
  
  
  ## Content 2: Sars-Cov2 Analysis
  * 2023-04-2? 
  > A
  
  > A
  
  ## Content 3: DEG Analysis
    * 2023-05-08
  > Differential gene expression of leishmaniasis

  > RNA seq 데이터를 바탕으로 transcriptomic profiling으로 다양한 형태의 DEG분석을 실습한다. 
    <p align="left">
   </p>
  1. TMP 계산 및 scatter plot
    <p align="left">
   </p>
  2. TMP correlation 확인 (정상 vs leishmania군 구별)
    <p align="left">
   </p>
  3. TMP상의 문제점 확인 : 1) 유전자 길이로 보정해서 짧은 read결과에서 편향 발생(<->RPKM)
                           2) 다른 샘플과의 비교가 부적절
      <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/d7a9dc9c-d5ce-4697-a9bb-2a4b80a15288" alt="image" width="auto" height="100">
   </p>
  4. MA plot 으로 두 그룹(조건) 비교, 이상치 확인
  5. TMM 방식으로 분포 차이나는 두 그룹의 발현량을 가중치로 정규화
      <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/8d079af5-5b32-4ea7-a821-160a44547082" alt="image" width="auto" height="100">
   </p>
  6. PCA analysis
      <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/ec0e0f89-1106-4cb1-b785-594141cfde2c" alt="image" width="auto" height="100">
   </p>
  7. Volcano plot : 발현량 Fold change와 p-value를 바탕으로 타겟 선정
      <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/2bae2935-d3e5-4256-bca2-3fcdb5959f72" alt="image" width="auto" height="100">
   </p>
  8. Heatmap으로 발현의 up/down reg.이 두 비교집단에서 다른 것을 확인
      <p align="left">
  <img src="https://github.com/WoobeenJeong/bioinfo1_jwb/assets/132027211/b2edd6fe-8a33-441e-b7bd-33d0a6ed7a36" alt="image" width="auto" height="100">
   </p>
  10. DAVID에서 타겟의 정보 확인
  
  [> CODE for content 3:](https://github.com/WoobeenJeong/bioinfo1_jwb/blob/main/geneexpr.ipynb)
  [file name] geneexpr.ipynb


