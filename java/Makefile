PREFIX=/usr
JSHARE=$(PREFIX)/share/java

all:
	ant jar


clean:
	ant clean

distclean: clean

install:
	install -d $(DESTDIR)$(JSHARE)
	install -m 0644 -t $(DESTDIR)$(JSHARE) build/jar/*.jar
