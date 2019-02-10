# Algorithmic-Strategic-Exercise


def bubble_sort(array)
    sorted = false  # when this var is false, that means the array is not fully sorted yet and so the loop continues

    while !sorted       
        sorted = true  
        
        (0...array.length - 1).each do |i| 
            if array[i] > array[i + 1]     
                array[i], array[i + 1] = array[i + 1], array[i]  
                sorted = false          
					   which loops back to  false
            end                                                     
        end

   array  
end
