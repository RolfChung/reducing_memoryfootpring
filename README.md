# reducing_memoryfootpring
Reducing the memory footprint with pandas on the museum of modern art data set.

<p>
The goal of this project is to optimize memory usage of large (or medium sized) data sets within Pandas. The data set used concerns the exhibitions of the <a href="https://www.moma.org/">Museum of modern art</a>. The data set is taken from <a href="https://data.world/moma/exhibitions">data world</a>. Thanks a lot for their good work!
</p> 

<p>
According to data world the exhibition index dataset was compiled by a project team from the MoMA Archives as part of their work to preserve, describe, and open to the public over 22,000 folders of exhibition records dating from 1929 to 1989 from its registrar and curatorial departments.            
<p>

<p>
Memory usage is a challenge when processing data for example with machine
learning algorithms. Memory usage can easily stress or override the 
memory capacity of a single machine, when working with medium size or large data sets. This can lead to hours of processing time. Of course it is possible to employ more machines with parallel computing and use tools like <a href="https://spark.apache.org/"> Spark</a> or others.</p>
    
<p>
There are of course repercussions. For example the
fine data analysis capabilities of Pandas are not matched every time 
with tools like <a href="https://dask.org/">Dask </a> for now. Also
as user friendly those tools often are those require set up time. Often you would like to do at least initial work on a single machine, before moving on or not. In this case determining the memory footprint and optimizing data processing comes in handy. 
Besides Pandas works easily with different SQL tools, which can
further reduce the memory footprint.
</p>

<p>
For optimizing data processing the following tasks are carried out here:
</p>

<ul>

<li>data import</li>
<li>data visualization</li>
<li>make use of arguments of read_csv</li>  
<li>understanding the memory footprint</li>
<li>calculating memory size on different levels</li>
<li>understanding the influence of data types on the the memory footprint</li>  
<li>finding the subdatatype, which stores a variablewith the lowest memory footprint</li>
<li>dealing with categorical variables</li>
<li>calculating memory savings</li>
<li>reading in data with chunks</li>
<li>combining values generated within each chunk into one total object as a pandas series and benchmark with timeit</li>

</ul>
    
<p>
Comments are and explanations are given within the coding.
A conclusion is made at the end.
</p> 

