targets = all clean install

.PHONY: $(targets)
$(targets):
	$(MAKE) -C trusted $@
	$(MAKE) -C untrusted $@

