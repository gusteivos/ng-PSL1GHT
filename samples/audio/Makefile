TARGETS := audiosync audiotest

all:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET; done

pkg:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET pkg; done

clean:
	@for TARGET in $(TARGETS); do $(MAKE) --no-print-directory -C $$TARGET clean; done
