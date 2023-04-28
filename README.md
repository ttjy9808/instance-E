for i,v in next, getgc(true) do
                if type(v) == "table" and rawget(v, "ID") and rawget(v, "Seconds") then
                    if typeof(v.Seconds) == "number" then
                        rawset(v, "Seconds", 0.001)
                    end
                end
            end
