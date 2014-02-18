for android:

System.exit(1);  退出

//侦听返回按钮
stage.addEventListener(KeyboardEvent.KEY_UP, function k(event:KeyboardEvent) {
			if (event.keyCode == 27){
				event.stopImmediatePropagation();
				event.stopPropagation();
				handleBackButton();
				}
			});
