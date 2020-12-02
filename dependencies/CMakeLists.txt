
include(FetchContent)

FetchContent_Declare(sqlpp_mysql
    GIT_REPOSITORY  https://github.com/rbock/sqlpp11-connector-mysql
    GIT_TAG         origin/master
)

add_subdirectory(sqlpp_mysql)
