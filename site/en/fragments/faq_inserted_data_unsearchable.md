This is because the data has not been flushed from memory to disk. To ensure that data can be searched immediately after insertion, you can call <code>flush</code>. However, calling this method too often creates too many small files and affects search speed.