

TESTS := \
  typecheck.ml \
  pattern.ml \
  eval.ml \

all: 
	@for i in $(TESTS); do \
		echo "--- Running Test:" `echo $$i | sed 's/\\.ml//'` "---"; \
		./unit_test $$i;\
	done

clean: 
	make -C .. clean