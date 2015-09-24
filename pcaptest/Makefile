CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =	pcap.o

LIBS =	-lpcap

TARGET =	pcap

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
