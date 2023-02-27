```dataview
list
from (#Session AND "Settings/Zobror")
where contains(PCs, this.file.name)
sort session-date ASC
>```