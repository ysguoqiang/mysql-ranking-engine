SET(RANKING_PLUGIN_DYNAMIC "ha_ranking")
SET(RANKING_SOURCES ha_ranking.cc)
MYSQL_ADD_PLUGIN(ranking ${RANKING_SOURCES} STORAGE_ENGINE MODULE_ONLY)
