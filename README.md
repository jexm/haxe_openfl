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






//Still no hit test for HTML5 target ?
public static inline function hitTest(obj1:Sprite, obj2:Sprite):Bool
{
   var a:Rectangle = obj1.getBounds(obj1.parent);
   var b:Rectangle = obj2.getBounds(obj2.parent);
   return a.intersects(b);
}
