��#   C l a s s i f i c a t i o n   o f   d a t a   s t r u c t u r e s  
  
 C l a s s i f i c a t i o n   f a c t o r s   o f   c o m p l e x   d a t a   s t r u c t u r e s .  
  
 1 .   T y p e   o f   e l e m e n t s  
     -   _ _ H o m o g e n e o u s ( s o l i d ) _ _ :   i f   e l e m e n t s   m u s t   h a v e   t h e   s a m e   t y p e  
     -   _ _ H e t e r o g e n e o u s _ _ :   i f   e l e m e n t s   n e e d   n o t   b e   o f   t h e   s a m e   t y p e  
  
 2 .   E l e m e n t   r e l a t i o n s h i p  
     -   _ _ U n s t r u c t u r e d _ _ :          
     n o   r e l a t i o n s h i p   b e t w e e n   t h e   e l e m e n t s .  
     -   _ _ A s s o c i a t i v e _ _ :          
     n o   e s s e n t i a l   r e l a t i o n s h i p s   b e t w e e n   t h e   e l e m e n t s ,   e l e m e n t s   a r e   i n d i v i d u a l l y   a d d r e s s a b l e .   E x a m p l e :   a r r a y .  
     -   _ _ S e q u e n t i a l _ _ :        
     e v e r y   e l e m e n t   i s   r e f e r e n c e d   b y   e x a c t l y   o n e   ( p a r t i c u l a r )   o t h e r   e l e m e n t ;   e v e r y   e l e m e n t   h a s   a   s i n g l e   r e f e r e n c e   t o   t h e   ( p a r t i c u l a r )   o t h e r   e l e m e n t .   E x a m p l e :   l i n e a r   s i n g l y - l i n k e d   l i s t .   T h e   f i r s t   e l e m e n t   i s   a   p o s s i b l e   e x c e p t i o n ,   i f   t h e   D S   i s   n o t   c i r c u l a r ,   a l t h o u g h   t h e   f i r s t   e l e m e n t   i s   t h e n   r e f e r e n c e d   b y   a n o t h e r   s t r u c t u r e   ( t h e   s t r u c t u r e   t h a t   r e p r e s e n t s   t h e   l i s t   a s   a   w h o l e ) .  
     -   _ _ H i e r a r c h i c a l _ _ :        
     t h e s e   D S   a r e   s e l f - s i m i l a r :   t h e r e   i s   a   m a i n   e l e m e n t   ( n o d e ) ,   c a l l e d   r o o t ,   t h a t   h a s   ( p r e d e t e r m i n e d   n u m b e r   o f )   c h i l d r e n   n o d e s ;   E v e r y   n o d e   ( e x c e p t   t h e   r o o t )   i s   r e f e r e n c e d   b y   e x a c t l y   o n e   o t h e r   p a r t i c u l a r   e l e m e n t ;   e a c h   n o d e   r e f e r e s   t o   a r b i t r a r y ,   b u t   p r e d e t e r m i n e d ,   n u m b e r   o f   ( c h i l d )   n o d e s .   E x a m p l e :   b i n a r y   t r e e .  
     -   _ _ L a t t i c e   ( n e t ) _ _ :        
     e l e m e n t s   ( n o d e s )   c a n   b e   r e f e r e n c e d   b y   s e v e r a l   o t h e r   n o d e s ;   e a c h   n o d e   h a s   m u l t i p l e   r e f e r e n c e s   t o   o t h e r   n o d e s .   E x a m p l e :   g r a p h .  
  
 3 .   N u m b e r   o f   e l e m e n t s  
     -   _ _ S t a t i c _ _ :   t h e   n u m b e r   o f   e l e m e n t s   i s   c o n s t a n t .   A l l   t h e   n e e d e d   s p a c e   i s   a l l o c a t e d   i n   a d v a n c e   a n d   i t   s t a y s   f i x e d .  
     -   _ _ D y n a m i c _ _ :   t h e   n u m b e r   o f   e l e m e n t s   v a r i e s .   S p a c e   f o r   e a c h   e l e m e n t   h a s   t o   b e   a l l o c a t e d   u p o n   t h e   e l e m e n t ' s   c r e a t i o n .  
  
 4 .   L o c a t i o n   o f   e l e m e n t s  
     -   _ _ C o n t i n u a l _ _ :   e l e m e n t s   a r e   l a y e d   o u t   s e q u e n t i a l l y   i n   c o n t i g u o u s   s p a c e .  
     -   _ _ D i f f u s e d   ( l i n k e d ) _ _ :   e l e m e n t s   a r e   l o c a t e d   r a n d o m l y ;   t h e   l o c a t i o n   o f   e a c h   e l e m e n t   i s   t r a c k e d   b y   a   p o i n t e r . 