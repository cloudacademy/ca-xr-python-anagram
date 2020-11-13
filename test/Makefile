TARGET_DIR = ../challenge/one/

one:
	mkdir -p $(TARGET_DIR)
	cp -f ../src/*.py $(TARGET_DIR)
	cp -f ./*.py $(TARGET_DIR)
	cd $(TARGET_DIR); python3 -B -m pytest *_test.py