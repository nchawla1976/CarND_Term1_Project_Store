for i = 1:5
   
    myinputfilename = sprintf('Web_Trafficsign_image%d.jpg',i);
    myoutputfilename = sprintf('Web_Trafficsign_scaled_image%d.jpg',i);
    temp = imread(myinputfilename);
    temp_resize = imresize(temp,[32 32],'bicubic');
    imwrite(temp_resize,myoutputfilename);
    
end
    