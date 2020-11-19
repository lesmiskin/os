* sudo apt-get install nasm -y			# assembly language compiler
* sudo apt-get install bvi -y 			# binary editor
* sudo apt-get install qemu-system-x86 -y	# x86 emulator

* nasm boot.asm -f bin -o boot.bin		# compile asm to machine code
* qemu-system-x86_64 boot.bin			# run OS

