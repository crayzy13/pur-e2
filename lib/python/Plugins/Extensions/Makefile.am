installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner MediaPlayer SocketMMI DVDBurn Volume_adjust ProgrammlistenUpdater

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if VUSOLO4K
SUBDIRS += MiniTV QuadPip
endif

if VUULTIMO4K
SUBDIRS += MiniTV QuadPip
endif

if VUUNO4K
SUBDIRS += QuadPip
endif

if HAVE_WETEK_XBMC
SUBDIRS +=  StartKodi
endif

install_PYTHON = __init__.py
