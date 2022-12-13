//Chay cac tac vu tuan tu
Thread(target=rtsp_ftp_camera(Netsetting.cam_rtsp)).start() 
//Chay cac tac vu song song
Thread(target=rtsp_ftp_camera, args=(Netsetting.cam_rtsp)).start()
