#stretch Lightmap Sample

If you make the stage stretchd the Cube, it might be able to see the dirty shadow.

![image](notes/image1.jpg)

##What happen

Light map of UV are consistent with the UV of the object.
In other words, when you scale an object, might light map is extended.

![image](notes/image2.jpg)

![check resolution](notes/checkresolution.gif)

A simple scaling, the problem does not occur.

![simple scaling](http://cdn-ak.f.st-hatena.com/images/fotolife/t/tsubaki_t1/20160421/20160421000935.png)

##How to fix it?

lets generate lightmap uvs.

1.  export gameObject to OBJ files. by http://wiki.unity3d.com/index.php?title=ObjExporter
2.  check "generate lightmap uvs"
3.  replace gameObjects.

![generatelightmapuvs](notes/generatelightmapuvs.jpg)

or don't not use Baked GI.

#original article

http://tsubakit1.hateblo.jp/entry/2016/04/21/003737