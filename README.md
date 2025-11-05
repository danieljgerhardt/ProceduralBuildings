# Procedural Buildings - Lod's House

The goal is to procedurally generated houses that look like Lod's House from the hit game The Elder Scrolls V: Skyrim.

The tool can be used as seen in the following demo video:

https://github.com/user-attachments/assets/a22cb8d1-e07a-4db8-86a2-764884acc219



This is what Lod's Hosue looks like:
![200px-SR-place-Lod's_House](https://github.com/user-attachments/assets/d491e0a6-572c-4756-bf2e-e9f6672586f4)

It has a distinctive nordic style, with a triangular hay thatched roof. It has a front awning supported by log poles and an elevated porch. The side faces of the house also have log supports and are slightly indented.

Other similar nordic houses from Skyrim look like this:
![images](https://github.com/user-attachments/assets/0c454419-faa4-4208-9327-10142b705bbb)
![download](https://github.com/user-attachments/assets/9f70b755-04aa-4650-b7f5-5fc9af949ef4)

For a basic implementation, the most important assets are the walls and the roof. The walls are separated by logs with wooden panels, and a door is needed. The hay roof is also an essential component. It is a triangular prism that could most simply be decomposed into two triangles on the side walls attached by two rectangles.
