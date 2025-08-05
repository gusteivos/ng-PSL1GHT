TARGETS := blitting rsxtest rsxtest_dl rsxtest_flip rsxtest_spu rsxtest_tile # cairo jpgtest pngtest videoTest

all:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET; done

pkg:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET pkg; done

clean:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET clean; done
