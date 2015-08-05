# AndroidPopupWindow
//实例化弹出窗口
menuWindow = new MyPopupWindow(MainActivity.this);
//显示窗口设置layout在PopupWindow中显示的位置
menuWindow.showAtLocation(MainActivity.this.findViewById(R.id.main), Gravity.BOTTOM|Gravity.CENTER_HORIZONTAL, 0, 0); 
