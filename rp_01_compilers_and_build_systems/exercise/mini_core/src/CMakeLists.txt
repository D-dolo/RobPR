add_library(core_library SHARED
  utils/blob.cpp 
  # TODO add other .cpp files

  #Step 7: add all .cpp files in src of the project: on shell: find . | grep .cpp | cut -c 3- and paste the files below 
  messages/base_sensor_message.cpp
  messages/odometry_message.cpp
  messages/pose_message.cpp
  utils/blob.cpp
  utils/deserializer.cpp
  utils/identifiable.cpp
  utils/id_context.cpp
  utils/id_placeholder.cpp
  utils/object_data.cpp
  utils/property.cpp
  utils/property_container.cpp
  utils/property_container_manager.cpp
  utils/property_eigen.cpp
  utils/property_identifiable.cpp
  utils/serializable.cpp
  utils/serialization_context.cpp
  utils/serializer.cpp

)
 #step 8: go to executables folder