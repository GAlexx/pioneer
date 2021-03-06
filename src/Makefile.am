## Process this file with automake to produce Makefile.in
SUBDIRS = collider gui render

include $(top_srcdir)/Makefile.common

AM_CFLAGS += $(WARN_CFLAGS)
AM_CPPFLAGS += $(WARN_CPPFLAGS)
AM_CXXFLAGS += $(WARN_CXXFLAGS)

bin_PROGRAMS = pioneer modelviewer
noinst_HEADERS = \
	Aabb.h \
	AmbientSounds.h \
	Background.h \
	BezierCurve.h \
	Body.h \
	BufferObject.h \
	CargoBody.h \
	ChatForm.h \
	CityOnPlanet.h \
	Color.h \
	CommodityTradeWidget.h \
	CustomSystem.h \
	DeadVideoLink.h \
	DeleteEmitter.h \
	DynamicBody.h \
	EquipType.h \
	FaceVideoLink.h \
	Font.h \
	FontManager.h \
	Form.h \
	FormController.h \
	Frame.h \
	GalacticView.h \
	Galaxy.h \
	GameMenuView.h \
	GeoSphere.h \
	GeoSphereStyle.h \
	HyperspaceCloud.h \
	InfoView.h \
	IniConfig.h \
	GameConfig.h \
	FontConfig.h \
	KeyBindings.h \
	Lang.h \
	LmrModel.h \
	LuaBody.h \
	LuaCargoBody.h \
	LuaChatForm.h \
	LuaConsole.h \
	LuaConstants.h \
	LuaEngine.h \
	LuaEquipType.h \
	LuaEventQueue.h \
	LuaFormat.h \
	LuaGame.h \
	LuaManager.h \
	LuaMusic.h \
	LuaNameGen.h \
	LuaObject.h \
	LuaPlanet.h \
	LuaPlayer.h \
	LuaRand.h \
	LuaSBody.h \
	LuaSystemPath.h \
	LuaSerializer.h \
	LuaShip.h \
	LuaShipType.h \
	LuaSpace.h \
	LuaSpaceStation.h \
	LuaStar.h \
	LuaStarSystem.h \
	LuaTimer.h \
	LuaUI.h \
	LuaUtils.h \
	MarketAgent.h \
	Missile.h \
	ModelBody.h \
	MyLuaMathTypes.h \
	NameGenerator.h \
	Object.h \
	ObjectViewerView.h \
	PersistSystemData.h \
	Pi.h \
	PiLuaClasses.h \
	Planet.h \
	Player.h \
	Polit.h \
	Projectile.h \
	Quaternion.h \
	RefCounted.h \
	RefList.h \
	Sector.h \
	SectorView.h \
	Serializer.h \
	StationAdvertForm.h \
	StationBulletinBoardForm.h \
	StationCommodityMarketForm.h \
	StationPoliceForm.h \
	StationServicesForm.h \
	StationShipEquipmentForm.h \
	StationShipMarketForm.h \
	StationShipRepairForm.h \
	StationShipViewForm.h \
	StationShipyardForm.h \
	StringF.h \
	Sfx.h \
	Ship.h \
	ShipAICmd.h \
	ShipCpanel.h \
	ShipCpanelMultiFuncDisplays.h \
	ShipFlavour.h \
	ShipSpinnerWidget.h \
	ShipType.h \
	Sound.h \
	SoundMusic.h \
	Space.h \
	SpaceStation.h \
	SpaceStationView.h \
	Star.h \
	StarSystem.h \
	SystemInfoView.h \
	SystemPath.h \
	SystemView.h \
	TerrainBody.h \
	TextureFont.h \
	TextureManager.h \
	VectorFont.h \
	VideoLink.h \
	View.h \
	WorldView.h \
	buildopts.h \
	fixed.h \
	gameconsts.h \
	libs.h \
	matrix4x4.h \
	mtrand.h \
	perlin.h \
	utils.h \
	vector3.h

pioneer_SOURCES	= \
	AmbientSounds.cpp \
	Background.cpp \
	Body.cpp \
	CargoBody.cpp \
	ChatForm.cpp \
	CityOnPlanet.cpp \
	CommodityTradeWidget.cpp \
	CustomSystem.cpp \
	DeadVideoLink.cpp \
	DynamicBody.cpp \
	EquipType.cpp \
	FaceVideoLink.cpp \
	Font.cpp \
	FontManager.cpp \
	FormController.cpp \
	Frame.cpp \
	GalacticView.cpp \
	Galaxy.cpp \
	GameMenuView.cpp \
	GeoSphere.cpp \
	GeoSphereStyle.cpp \
	HyperspaceCloud.cpp \
	InfoView.cpp \
	IniConfig.cpp \
	GameConfig.cpp \
	FontConfig.cpp \
	KeyBindings.cpp \
	Lang.cpp \
	LmrModel.cpp \
	LuaBody.cpp \
	LuaCargoBody.cpp \
	LuaChatForm.cpp \
	LuaConsole.cpp \
	LuaConstants.cpp \
	LuaEngine.cpp \
	LuaEquipType.cpp \
	LuaEventQueue.cpp \
	LuaFormat.cpp \
	LuaGame.cpp \
	LuaManager.cpp \
	LuaMusic.cpp \
	LuaNameGen.cpp \
	LuaObject.cpp \
	LuaPlanet.cpp \
	LuaPlayer.cpp \
	LuaRand.cpp \
	LuaSBody.cpp \
	LuaSystemPath.cpp \
	LuaSerializer.cpp \
	LuaShip.cpp \
	LuaShipType.cpp \
	LuaSpace.cpp \
	LuaSpaceStation.cpp \
	LuaStar.cpp \
	LuaStarSystem.cpp \
	LuaTimer.cpp \
	LuaUI.cpp \
	LuaUtils.cpp \
	MarketAgent.cpp \
	Missile.cpp \
	ModelBody.cpp \
	MyLuaMathTypes.cpp \
	NameGenerator.cpp \
	ObjectViewerView.cpp \
	Pi.cpp \
	PiLuaClasses.cpp \
	Planet.cpp \
	Player.cpp \
	Polit.cpp \
	Projectile.cpp \
	Sector.cpp \
	SectorView.cpp \
	Serializer.cpp \
	StationAdvertForm.cpp \
	StationBulletinBoardForm.cpp \
	StationCommodityMarketForm.cpp \
	StationPoliceForm.cpp \
	StationServicesForm.cpp \
	StationShipEquipmentForm.cpp \
	StationShipMarketForm.cpp \
	StationShipRepairForm.cpp \
	StationShipViewForm.cpp \
	StationShipyardForm.cpp \
	StringF.cpp \
	Sfx.cpp \
	Ship-AI.cpp \
	Ship.cpp \
	ShipAICmd.cpp \
	ShipCpanel.cpp \
	ShipCpanelMultiFuncDisplays.cpp \
	ShipFlavour.cpp \
	ShipSpinnerWidget.cpp \
	ShipType.cpp \
	Sound.cpp \
	SoundMusic.cpp \
	Space.cpp \
	SpaceStation.cpp \
	SpaceStationView.cpp \
	Star.cpp \
	StarSystem.cpp \
	SystemInfoView.cpp \
	SystemView.cpp \
	TerrainBody.cpp \
	TextureFont.cpp \
	TextureManager.cpp \
	VectorFont.cpp \
	WorldView.cpp \
	main.cpp \
	mtrand.cpp \
	perlin.cpp \
	utils.cpp

pioneer_LDADD = ../contrib/oolua/liboolua.a collider/libcollider.a gui/libgui.a render/librender.a \
		$(MINGW_LIBS) \
		$(FREETYPE_LIBS) $(GLEW_LIBS) $(GLU_LIBS) $(GL_LIBS) \
		$(SDL_LIBS) $(SIGC_LIBS) $(LUA_LIBS) $(VORBIS_LIBS) \
		$(PNG_LIBS)
if !HAVE_LUA
pioneer_LDADD += ../contrib/lua/liblua.a
endif

modelviewer_SOURCES = \
	Font.cpp \
	IniConfig.cpp \
	FontConfig.cpp \
	FontManager.cpp \
	LmrModel.cpp \
	LuaModelViewer.cpp \
	LuaUtils.cpp \
	MyLuaMathTypes.cpp \
	StringF.cpp \
	TextureFont.cpp \
	TextureManager.cpp \
	VectorFont.cpp \
	perlin.cpp \
	utils.cpp
modelviewer_LDADD = collider/libcollider.a gui/libgui.a render/librender.a \
		    $(MINGW_LIBS) \
		    $(FREETYPE_LIBS) $(GLEW_LIBS) $(GLU_LIBS) $(GL_LIBS) \
		    $(SDL_LIBS) $(SIGC_LIBS) $(LUA_LIBS) $(PNG_LIBS)
if !HAVE_LUA
modelviewer_LDADD += ../contrib/lua/liblua.a
endif

check_PROGRAMS = tests
tests_SOURCES = \
	StringF.cpp \
	tests.cpp \
	test_Frame.cpp \
	test_StringF.cpp

TESTS = tests
 
tests_LDADD = collider/libcollider.a gui/libgui.a render/librender.a

INCLUDES = -isystem @top_srcdir@/contrib
if !HAVE_LUA
INCLUDES += -isystem @top_srcdir@/contrib/lua
endif
