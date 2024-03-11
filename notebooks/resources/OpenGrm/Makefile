make all: collapse.far expand.far

collapse.far: collapse.grm byte.far inverse.far
	thraxcompiler --input_grammar=$< --output_far=$@

expand.far: expand.grm byte.far numbers.far abbrevs.far declensions.far
	thraxcompiler --input_grammar=$< --output_far=$@

byte.far: byte.grm
	thraxcompiler --input_grammar=$< --output_far=$@

numbers.far: numbers.grm byte.far
	thraxcompiler --input_grammar=$< --output_far=$@

abbrevs.far: abbrevs.grm
	thraxcompiler --input_grammar=$< --output_far=$@

declensions.far: declensions.grm
	thraxcompiler --input_grammar=$< --output_far=$@

inverse.far: inverse.grm
	thraxcompiler --input_grammar=$< --output_far=$@

clean:
	rm -f byte.far numbers.far abbrevs.far declensions.far inverse.far
