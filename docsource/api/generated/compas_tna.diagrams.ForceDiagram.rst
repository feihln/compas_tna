.. rst-class:: detail

ForceDiagram
================================

.. currentmodule:: compas_tna.diagrams

.. autoclass:: ForceDiagram

    
    

    .. rubric:: Attributes

    .. autosummary::
    

    .. rubric:: Inherited Attributes

    .. autosummary::
    
        ~ForceDiagram.adjacency
        ~ForceDiagram.data
        ~ForceDiagram.name

    
    

    
    

    .. rubric:: Methods

    .. autosummary::
        :toctree:

    
        ~ForceDiagram.__init__
        ~ForceDiagram.draw
        ~ForceDiagram.fixed
        ~ForceDiagram.from_formdiagram
        ~ForceDiagram.get_form_edge_attribute
        ~ForceDiagram.ordered_edges
        ~ForceDiagram.plot
        ~ForceDiagram.uv_index

    .. rubric:: Inherited Methods

    .. autosummary::
        :toctree:

    
        ~ForceDiagram.add_face
        ~ForceDiagram.add_vertex
        ~ForceDiagram.area
        ~ForceDiagram.boundaries
        ~ForceDiagram.centroid
        ~ForceDiagram.clear
        ~ForceDiagram.clear_facedict
        ~ForceDiagram.clear_halfedgedict
        ~ForceDiagram.clear_vertexdict
        ~ForceDiagram.copy
        ~ForceDiagram.cull_edges
        ~ForceDiagram.cull_vertices
        ~ForceDiagram.delete_face
        ~ForceDiagram.delete_vertex
        ~ForceDiagram.dump
        ~ForceDiagram.dumps
        ~ForceDiagram.edge_coordinates
        ~ForceDiagram.edge_direction
        ~ForceDiagram.edge_faces
        ~ForceDiagram.edge_label_name
        ~ForceDiagram.edge_length
        ~ForceDiagram.edge_midpoint
        ~ForceDiagram.edge_name
        ~ForceDiagram.edge_point
        ~ForceDiagram.edge_vector
        ~ForceDiagram.edges
        ~ForceDiagram.edges_on_boundary
        ~ForceDiagram.edges_where
        ~ForceDiagram.edges_where_predicate
        ~ForceDiagram.euler
        ~ForceDiagram.face_adjacency_halfedge
        ~ForceDiagram.face_adjacency_vertices
        ~ForceDiagram.face_area
        ~ForceDiagram.face_aspect_ratio
        ~ForceDiagram.face_center
        ~ForceDiagram.face_centroid
        ~ForceDiagram.face_coordinates
        ~ForceDiagram.face_corners
        ~ForceDiagram.face_curvature
        ~ForceDiagram.face_degree
        ~ForceDiagram.face_flatness
        ~ForceDiagram.face_halfedges
        ~ForceDiagram.face_label_name
        ~ForceDiagram.face_max_degree
        ~ForceDiagram.face_min_degree
        ~ForceDiagram.face_name
        ~ForceDiagram.face_neighbors
        ~ForceDiagram.face_normal
        ~ForceDiagram.face_skewness
        ~ForceDiagram.face_vertex_ancestor
        ~ForceDiagram.face_vertex_descendant
        ~ForceDiagram.face_vertices
        ~ForceDiagram.faces
        ~ForceDiagram.faces_on_boundary
        ~ForceDiagram.faces_where
        ~ForceDiagram.faces_where_predicate
        ~ForceDiagram.from_data
        ~ForceDiagram.from_json
        ~ForceDiagram.from_lines
        ~ForceDiagram.from_obj
        ~ForceDiagram.from_off
        ~ForceDiagram.from_pickle
        ~ForceDiagram.from_ply
        ~ForceDiagram.from_points
        ~ForceDiagram.from_polygons
        ~ForceDiagram.from_polyhedron
        ~ForceDiagram.from_stl
        ~ForceDiagram.from_vertices_and_faces
        ~ForceDiagram.genus
        ~ForceDiagram.get_any_edge
        ~ForceDiagram.get_any_face
        ~ForceDiagram.get_any_face_vertex
        ~ForceDiagram.get_any_vertex
        ~ForceDiagram.get_any_vertices
        ~ForceDiagram.get_continuous_edges
        ~ForceDiagram.get_edge_attribute
        ~ForceDiagram.get_edge_attributes
        ~ForceDiagram.get_edges_attribute
        ~ForceDiagram.get_edges_attributes
        ~ForceDiagram.get_edges_of_opening
        ~ForceDiagram.get_face_attribute
        ~ForceDiagram.get_face_attributes
        ~ForceDiagram.get_faces_attribute
        ~ForceDiagram.get_faces_attributes
        ~ForceDiagram.get_parallel_edges
        ~ForceDiagram.get_vertex_attribute
        ~ForceDiagram.get_vertex_attributes
        ~ForceDiagram.get_vertices_attribute
        ~ForceDiagram.get_vertices_attributes
        ~ForceDiagram.gkey_key
        ~ForceDiagram.has_edge
        ~ForceDiagram.has_vertex
        ~ForceDiagram.index_key
        ~ForceDiagram.index_uv
        ~ForceDiagram.insert_vertex
        ~ForceDiagram.is_edge_on_boundary
        ~ForceDiagram.is_empty
        ~ForceDiagram.is_face_on_boundary
        ~ForceDiagram.is_manifold
        ~ForceDiagram.is_orientable
        ~ForceDiagram.is_quadmesh
        ~ForceDiagram.is_regular
        ~ForceDiagram.is_trimesh
        ~ForceDiagram.is_valid
        ~ForceDiagram.is_vertex_connected
        ~ForceDiagram.is_vertex_on_boundary
        ~ForceDiagram.key_gkey
        ~ForceDiagram.key_index
        ~ForceDiagram.leaves
        ~ForceDiagram.load
        ~ForceDiagram.loads
        ~ForceDiagram.normal
        ~ForceDiagram.number_of_edges
        ~ForceDiagram.number_of_faces
        ~ForceDiagram.number_of_vertices
        ~ForceDiagram.set_edge_attribute
        ~ForceDiagram.set_edge_attributes
        ~ForceDiagram.set_edges_attribute
        ~ForceDiagram.set_edges_attributes
        ~ForceDiagram.set_face_attribute
        ~ForceDiagram.set_face_attributes
        ~ForceDiagram.set_faces_attribute
        ~ForceDiagram.set_faces_attributes
        ~ForceDiagram.set_vertex_attribute
        ~ForceDiagram.set_vertex_attributes
        ~ForceDiagram.set_vertices_attribute
        ~ForceDiagram.set_vertices_attributes
        ~ForceDiagram.summary
        ~ForceDiagram.to_data
        ~ForceDiagram.to_json
        ~ForceDiagram.to_obj
        ~ForceDiagram.to_pickle
        ~ForceDiagram.to_vertices_and_faces
        ~ForceDiagram.update_default_edge_attributes
        ~ForceDiagram.update_default_face_attributes
        ~ForceDiagram.update_default_vertex_attributes
        ~ForceDiagram.vertex_area
        ~ForceDiagram.vertex_coordinates
        ~ForceDiagram.vertex_curvature
        ~ForceDiagram.vertex_degree
        ~ForceDiagram.vertex_faces
        ~ForceDiagram.vertex_label_name
        ~ForceDiagram.vertex_laplacian
        ~ForceDiagram.vertex_max_degree
        ~ForceDiagram.vertex_min_degree
        ~ForceDiagram.vertex_name
        ~ForceDiagram.vertex_neighborhood
        ~ForceDiagram.vertex_neighborhood_centroid
        ~ForceDiagram.vertex_neighbors
        ~ForceDiagram.vertex_normal
        ~ForceDiagram.vertices
        ~ForceDiagram.vertices_on_boundaries
        ~ForceDiagram.vertices_on_boundary
        ~ForceDiagram.vertices_where
        ~ForceDiagram.vertices_where_predicate

    
    