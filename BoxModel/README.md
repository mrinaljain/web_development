# Boxmodel

 ## Content - Box ( width ko defined width se zyada kr deta hai)
 - The width and height you assign to an element is applied only to the element's content box. If the element has any border or padding, this is then added to the width and height to arrive at the size of the box that's rendered on the screen. 
 - jab bhi width property doge to uske uppar padding aur border add hogi aur phir screen pr paint hogi
 - example 
  width : 200px
  border 10 px
  padding 20px

  final width : 200 + 10 + 10 + 20 + 20 = 260 px ( dono side ki padding aur  border bi add ho gyi)


 ## Border - Box ( width ko defined width se zyada nhi hone deta)


 the final width of the box is callculated just with the contents width and the  border , padding are ignored

 - jab bhi element ko width dete hai to vahi width  screen pr render hogi 
 - uss given width ka andar hi padding aur border bhi adjust hogi
 