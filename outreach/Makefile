outreach=outreach.md
media=media.md

all: $(outreach) $(media)

$(outreach): outreach.yaml generate_outreach.py outreach.head
	cp outreach.head $@
	./generate_outreach.py < $< >> $@

$(media): media.yaml generate_outreach.py media.head
	cp media.head $@
	./generate_outreach.py < $< >> $@
