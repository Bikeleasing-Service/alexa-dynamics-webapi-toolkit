## February 2024

During the implementation of a new feature we realized that MS Dynamics is
no (longer?) returning the complete list of outbound relationships for an
entity when querying the metadata. 

This leads to the serializer not being able to resolve the attributes and
not serializing the entity correctly, with data loss. 

The small fix here doesn't want to be a complete solution, but a workaround
for the time being.