# 영상품질비교지표를 측정하는 매크로입니다.  
#### ssimm, psnr, mse, rmse를 측정합니다.
#### icy프로그램 위에서 파이썬이 돌아는 형태입니다.  

1. pynd파일에 들어가서 비교할 영상들이 있는 위치를 path폴더 안의 txt파일로 저장하는 작업을 합니다.

2. comparator.py에 들어가서 경로,좌표를 재설정합니다.

3. icy프로그램에 들어갑니다.

4. comparator 탭에 들어가서 최대창으로 한다음 아래로 내려놓고 파일열기가 보이는 탭을 활성화합니다.

5. 준비를 마쳤으면 cmd 관리자모드로 들어가 아래와같은 코드를 입력합니다.  
python comparator.py


