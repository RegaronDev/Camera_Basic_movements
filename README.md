# Camera_Basic_movements
the spatial code
(orbit rotationY): 

extends Spatial


func _physics_process(delta):
	
	if Input.is_action_pressed("ui_left"):
		rotate_y(-0.01)

	
	if Input.is_action_pressed("ui_right"):
		rotate_y(0.01)

the camera code 
(self rotationY):

extends Camera


func _physics_process(delta):
	
	if Input.is_action_pressed("Cam_left"):
		rotate_y(-0.01)

	
	if Input.is_action_pressed("Cam_right"):
		rotate_y(0.01)

 
