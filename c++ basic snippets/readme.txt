This code snippet set is for visual studio 2017. It might have a chance to work as well on visual studio 2015 and 2019. Not tested yet.

First thing first. This snippet set only helps a little bit. Don't rely on it too much. It provides no suggestions from logic. It only helps with spelling.

<Snippet grammar help>
In vs 2017 editor, main menu->Tool->Code snippets manager, it opens a popup window. In that window, 2 directory paths are shown. One is the default snippet set provided by Microsoft, the other is for custum.
Specially, under the xml snippet set,Snippets//Snippet, a template for creating new snippets. That file shows how to specify multiple jumping point within one snippet.

Notice grammar for snippets in visual studio 201x is different from in vs code. UE4 snippet set for vs code is already available on github. So, this set is kinda equivalent but organized according my habit.

Tips. To jump around auto jumping points within a snippet, press tab key. To jump to the $end$, press enter key.

In the <header><short cut>, if you specify this field with something contains any symbol other than ~ or #(only ~#$._ and space are tested till now.), after pressing tab key, you get absolutely the save as this field, no matter what you write afterward in the snippet file. So, if you would like to put any symbol in the short cut which shows in the intellisense popup window and not overwrites what you want, replace those symbol with ~ or #(or some other feasible ones).
In my set, I end up every short cut with ~UE4. If you type ~ue4 and ctrl J directly, you will see all of them.
</Snippet grammar help>


emmm, don't want to edit this any further. I plan to work on a ue4 snippet set after the cpp part is basicly done.


