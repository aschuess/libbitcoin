
file(GLOB MY_SOURCES "*.c")

ADD_LIBRARY(math_external STATIC
   ${MY_SOURCES}
   )

set_target_properties (math_external PROPERTIES
    FOLDER "libs/external"
)
 
