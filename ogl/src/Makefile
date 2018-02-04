#OBJS specifies which files to compile as part of the project
OBJS=shader.cpp texture.cpp controls.cpp main.cpp

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME=exe

#This is the target that compiles our executable
all :
	g++ $(OBJS) -w -lglfw -pthread -lGLEW -lGLU -lGL -lrt -lXrandr -lXxf86vm -lXi -lXinerama -lX11 -o $(OBJ_NAME)
