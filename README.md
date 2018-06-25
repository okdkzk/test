# test
cv2.VideoCapture()でVideoCaptureオブジェクトを取得.

　カメラから連続的に画像を取得するため、while文で繰り返し処理を行う. 
 while内の最初で、カメラから1コマのデータを取得するためcapture.read()を呼び出し. 取得した1コマの画像データは、変数frameに代入されています。

　OpenCVでcapture.read()で取得した画像データを指定します.cv2.imshow()メソッドを呼び出すと、自動的にフレーム(ウィンドウ)が立ち上がって画像を表示.

　whileを抜けると、処理を終了させるためにVideoCaptureを終了して、開いたウィンドウも終了.
