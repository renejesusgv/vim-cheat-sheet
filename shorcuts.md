select                                   v                                     
select row(s)                            SHIFT + v                             
select blocks (columns)                  CTRL  + v                             
indent selected text                     >                                     
unindent selected text                   <                                     
list buffers                             :ls                                   
open buffer                              :bN (N = buffer number)               
print                                    :hardcopy                             
open a file                              :e /path/to/file.txt                  
                                         :e C:\Path\To\File.txt                
sort selected rows                       :sort                                 
search for word under cursor             *                                     
open file under cursor                   gf                                    
  (absolute path or relative)                                                  
format selected code                     =                                     
select contents of entire file           ggVG                                  
convert selected text to uppercase       U                                     
convert selected text to lowercase       u                                     
invert case of selected text             ~                                     
convert tabs to spaces                   :retab                                
start recording a macro                  qX (X = key to assign macro to)       
stop recording a macro                   q                                       
playback macro                           @X (X = key macro was assigned to)    
replay previously played macro *         @@                                    
auto-complete a word you are typing **   CTRL + n                              
bookmark current place in file           mX (X = key to assign bookmark to)    
jump to bookmark                         `X (X = key bookmark was assigned to  
                                             ` = back tick/tilde key)          
show all bookmarks                       :marks                                
delete a bookmark                        :delm X (X = key bookmark to delete)   
delete all bookmarks                     :delm!                                 
split screen horizontally                :split                                
split screen vertically                  :vsplit                               
navigating split screens                 CTRL + w + j = move down a screen     
                                         CTRL + w + k = move up a screen       
                                         CTRL + w + h = move left a screen     
                                         CTRL + w + l = move right a screen    
close all other split screens            :only
remove all inside curly brackets(nm)     diB    
remove all inside parentheses			 dib
